# Security Policy

This repository powers a GitHub profile README. It contains no application
runtime code — only Markdown, static SVG assets, and GitHub Actions workflow
definitions — but it still runs Actions with write permissions and holds
secrets, so the usual reporting process applies.

## Supported Versions

Only the content on the `main` branch is maintained. `output` (snake
animation) and any workflow-committed files (`metrics.svg`, `stats.svg`,
`repositories.svg`, `profile-summary-card-output/`) are machine-generated —
don't hand-edit them, they're overwritten on the next scheduled run.

## Reporting a Vulnerability

If you find a security issue — a workflow misconfiguration that could leak
secrets, an overly broad token scope, or a supply-chain concern with one of
the third-party Actions used here (`Platane/snk`, `crazy-max/ghaction-github-pages`,
`lowlighter/metrics`, `vn7n24fzkq/github-profile-summary-cards`,
`jamesgeorge007/github-activity-readme`) — please report it privately:

- Email: **abdelhakimelazaly4@gmail.com**
- Include: the affected file/workflow, a description of the issue, and, if
  possible, suggested remediation.

There's no formal SLA (this is a personal repository, not a production
service), but reports are read and addressed promptly.

## Secrets & Token Hygiene

Two classic Personal Access Tokens are used across the workflows:

| Secret name | Used by | Minimum scope |
|---|---|---|
| `METRICS_TOKEN` | `metrics.yml`, `github-stats.yml`, `stats.yml` | `read:user` (add `repo` for private activity) |
| `SUMMARY_GITHUB_TOKEN` | `profile-summary.yml` | `read:user`, `repo` |

`snake.yml` and `recent-activity.yml` use the automatically provided
`GITHUB_TOKEN` and need no additional secret.

Guidelines:

- Grant the **minimum scopes** listed above — don't default to full `repo`
  + `admin` scopes out of convenience.
- Set an **expiration date** on every token and rotate on schedule.
- Never print or log token values in workflow output (none of the workflows
  in this repo do this — if you customize them, keep it that way).
- Every job here is scoped to `permissions: contents: write` only. No job
  requests organization-level or admin permissions.
