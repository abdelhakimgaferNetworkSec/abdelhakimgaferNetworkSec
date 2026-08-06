<div align="center">

<img src="assets/banner.svg" alt="Abdel Hakim Gafer — Network Security Engineer" width="100%"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=00FF99&center=true&vCenter=true&width=850&lines=Reducing+dwell+time+through+detection+engineering;Enterprise+Active+Directory+%2B+PKI+at+lab+scale;FortiGate+%E2%86%92+Wazuh+%2F+Splunk+%2F+Sentinel+pipelines;MITRE+ATT%26CK-mapped+correlation+rules;Closed-loop%3A+detect+%E2%86%92+contain+%E2%86%92+review" alt="Typing SVG"/>

<br/><br/>

<a href="https://linkedin.com/in/abdel-hakim-gafer-tech"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:abdelhakimelazaly4@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-00FF99?style=for-the-badge&logo=gmail&logoColor=black"/></a>
<a href="https://github.com/abdelhakimgaferNetworkSec"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=abdelhakimgaferNetworkSec&label=Profile%20Views&color=00FF99&style=for-the-badge"/>

<br/><br/>

<img src="https://img.shields.io/badge/Blue_Team-Detection_Engineering-0f2027?style=flat-square&labelColor=0f2027&color=00FF99"/>
<img src="https://img.shields.io/badge/SOC-Tier_2_Ready-0f2027?style=flat-square&labelColor=0f2027&color=00FF99"/>
<img src="https://img.shields.io/badge/MITRE_ATT%26CK-Mapped_Detections-0f2027?style=flat-square&labelColor=0f2027&color=00FF99"/>
<img src="https://img.shields.io/badge/Fortinet-NSE4-0f2027?style=flat-square&labelColor=0f2027&color=00FF99"/>

</div>

<br/>
<img src="assets/divider.svg" width="100%"/>
<br/>

## 🛡️ About Me

I design and operate detection pipelines — not just tool lists. My lab environment is built to the same architectural standards as a mid-size enterprise: a multi-tier **Active Directory forest** with least-privilege administration, an internal **Certificate Authority (AD CS)** issuing auto-enrolled certificates, a segmented **FortiGate** perimeter, and a detection stack spanning **Wazuh**, **Splunk Enterprise**, and **Microsoft Sentinel**.

The work that matters most to me happens after the log lands: writing decoders that parse it correctly, correlation rules that fire on the right signal instead of noise, and response automation that acts before an analyst has to. I map every rule I ship to **MITRE ATT&CK** so coverage — and gaps — stay visible, not assumed.

```yaml
role:              Network Security Engineer
specialization:    Detection Engineering / Blue Team / SIEM Engineering
lab_scope:         Enterprise-representative (AD + PKI + FortiGate + multi-SIEM)
operating_model:   Detect → Correlate → Automate → Verify
```

<details>
<summary><b>📈 Impact metrics (fill in with your real numbers — see note below)</b></summary>
<br/>

The bullets below are the categories recruiters and detection-engineering
interviewers actually screen for. Replace the placeholder figures with your
real lab measurements — quantified claims are what separate this section
from a tool list.

- **Detection coverage:** mapped `__` custom Wazuh/Sigma rules to `__` MITRE ATT&CK techniques across `__` tactics
- **Noise reduction:** cut false-positive rate on a specific rule set from `__%` to `__%` through tuning (state the before/after and what you changed)
- **Response time:** automated containment (IP block / process kill) reduces mean time-to-contain from `__` minutes (manual) to `__` seconds (automated)
- **Infrastructure scale:** lab simulates `__` endpoints across `__` VLANs/subnets, with `__` domain-joined hosts
- **Log throughput:** SIEM stack ingests roughly `__` events/day from FortiGate, Windows Event Forwarding, and Sysmon combined
- **Certificate lifecycle:** AD CS issues and auto-renews certificates for `__` templates across `__` device/user classes

> Why this matters: "reduced false positives" without a number is a claim;
> "38% → 6% FP rate after tuning three correlation rules" is evidence. Keep
> the ones you can defend in an interview and delete the rest.

</details>

<img src="assets/divider.svg" width="100%"/>

## ⚡ Core Focus

<table align="center">
<tr>
<td align="center" width="200">🔍 <b>Detection<br/>Engineering</b></td>
<td align="center" width="200">📡 <b>SIEM<br/>Engineering</b></td>
<td align="center" width="200">🖥️ <b>SOC<br/>Operations</b></td>
<td align="center" width="200">🕵️ <b>Threat<br/>Hunting</b></td>
</tr>
<tr>
<td align="center" width="200">🚨 <b>Incident<br/>Response</b></td>
<td align="center" width="200">🏢 <b>Active Directory<br/>Security</b></td>
<td align="center" width="200">🔐 <b>Enterprise<br/>PKI</b></td>
<td align="center" width="200">🤖 <b>Security<br/>Automation</b></td>
</tr>
</table>

<img src="assets/divider.svg" width="100%"/>

## 🧰 Security Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=windows,linux,ubuntu,kali,docker,git,github,vscode,py,bash"/>
</div>

<br/>

<table align="center">
<tr>
<th align="center">🔥 Firewalls</th>
<th align="center">📊 SIEM & Monitoring</th>
<th align="center">🎯 Detection</th>
<th align="center">🏗️ Infrastructure</th>
</tr>
<tr valign="top">
<td>

- FortiGate NGFW
- FortiManager
- FortiAnalyzer
- Site-to-Site VPN
- SSL VPN

</td>
<td>

- Wazuh
- Splunk Enterprise
- Microsoft Sentinel
- Elastic Stack

</td>
<td>

- Sigma Rules
- Sysmon
- Windows Event Forwarding
- YARA
- MITRE ATT&CK Mapping

</td>
<td>

- Active Directory
- Windows Server
- Microsoft AD CS (PKI)
- VMware / PNETLab

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%"/>

## 🏗️ Enterprise Lab Architecture

<div align="center">
<img src="assets/architecture.svg" alt="Enterprise security lab architecture diagram" width="100%"/>
</div>

<table align="center">
<tr valign="top">
<td width="50%">

**Identity & Trust**
- ✔ Enterprise Active Directory forest, multi-domain topology
- ✔ Group Policy–enforced security baselines (Microsoft baselines as floor, not ceiling)
- ✔ Tiered administration model (Tier 0/1/2 separation)
- ✔ Kerberos & NTLM hardening, LDAP signing/channel binding
- ✔ Enterprise PKI (AD CS): internal CA, certificate templates, auto-enrollment

</td>
<td width="50%">

**Network, Detection & Response**
- ✔ FortiGate NGFW with segmented zones and policy-based routing
- ✔ Site-to-Site and SSL VPN for remote/branch simulation
- ✔ Sysmon + Windows Event Forwarding feeding a centralized collector
- ✔ Wazuh, Splunk Enterprise, Elastic Stack, and Microsoft Sentinel in parallel for cross-platform detection comparison
- ✔ Active-response automation: brute-force mitigation, malicious process termination, automatic IP blocking

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%"/>

## 🚀 Projects

<table align="center">
<tr>
<td width="100%">

### 🛡️ Wazuh ↔ FortiGate Detection Pipeline

**Goal** — Get FortiGate perimeter events into a SIEM as structured, alertable data instead of raw syslog noise.

**Technologies** — Wazuh · FortiGate NGFW (syslog) · custom Wazuh decoders · Kibana/Wazuh dashboards

**Enterprise use case** — Mirrors how a mid-size org centralizes firewall telemetry for perimeter visibility: blocked-connection trends, VPN authentication anomalies, and policy-hit correlation surfaced in one pane instead of scattered across FortiGate's local logs.

**Skills demonstrated** — Log source onboarding, custom decoder/parser authoring, field normalization, dashboard design for SOC triage.

**Repository** — `github.com/abdelhakimgaferNetworkSec/wazuh-fortigate-pipeline` *(replace with your actual repo link)*

---

### 🔍 MITRE ATT&CK-Mapped Detection Rule Set

**Goal** — Build a detection rule library where every rule traces to a specific ATT&CK technique, with documented rationale and tested false-positive behavior.

**Technologies** — Sigma · Wazuh custom rules · MITRE ATT&CK Navigator · YARA (for file-based detections)

**Enterprise use case** — Answers the question every detection-engineering interview asks: "how do you know what you're NOT detecting?" A technique-mapped rule set turns that into a documented coverage matrix instead of a guess.

**Skills demonstrated** — Rule authoring in Sigma and native Wazuh syntax, ATT&CK technique mapping, systematic false-positive tuning methodology, detection-as-code version control.

**Repository** — `github.com/abdelhakimgaferNetworkSec/attck-detection-ruleset` *(replace with your actual repo link)*

---

### ⚡ Automated Active Response for Windows Endpoints

**Goal** — Close the loop between detection and containment for common attack patterns (brute force, suspicious process spawning) without waiting on manual analyst action.

**Technologies** — Wazuh Active Response · PowerShell · Windows Firewall API · Sysmon event triggers

**Enterprise use case** — Demonstrates the SOAR-adjacent skill set enterprises look for before investing in a full SOAR platform: scripted, auditable, reversible automated response tied directly to specific, tested trigger conditions.

**Skills demonstrated** — Response scripting, trigger/condition design to avoid over-blocking, rollback safety, IR playbook translation into executable automation.

**Repository** — `github.com/abdelhakimgaferNetworkSec/windows-active-response` *(replace with your actual repo link)*

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%"/>

## 🏆 Certifications

<div align="center">

<img src="https://img.shields.io/badge/Fortinet-NSE4-red?style=for-the-badge&logo=fortinet&logoColor=white"/>
<img src="https://img.shields.io/badge/FortiOS-Administrator-red?style=for-the-badge&logo=fortinet&logoColor=white"/>
<img src="https://img.shields.io/badge/Microsoft-AZ--900-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
<br/>
<img src="https://img.shields.io/badge/IBM-Cybersecurity_Fundamentals-052FAD?style=for-the-badge&logo=ibm&logoColor=white"/>
<img src="https://img.shields.io/badge/OPSWAT-ICIP-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Cisco-Intro_to_Cybersecurity-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white"/>

</div>

<img src="assets/divider.svg" width="100%"/>

## 🎯 2026 Roadmap

<table align="center">
<tr valign="top">
<td width="33%">

**Detection & Response**
- Advanced Microsoft Sentinel (KQL, analytics rules, automation)
- Splunk Enterprise Security
- SOAR platform evaluation
- Malware analysis fundamentals
- Digital forensics (DFIR)

</td>
<td width="33%">

**Offense-Informed Defense**
- Purple teaming exercises
- Adversary emulation-driven hunting

</td>
<td width="33%">

**Cloud & Modern Infra**
- Azure security (Defender for Cloud, Sentinel-native)
- General cloud security fundamentals
- Kubernetes security

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%"/>

## 📊 GitHub Analytics

> The cards below are generated by this repository's own GitHub Actions and
> committed as static files — not hot-linked to a shared, rate-limited
> public server. They populate automatically after the workflows run once
> (see `SETUP.md`).

<div align="center">

<img src="metrics.svg" alt="GitHub metrics dashboard" width="100%"/>

<br/><br/>

<img src="stats.svg" alt="Terminal-style core stats" width="100%"/>

<br/><br/>

<img src="repositories.svg" alt="Repository showcase" width="100%"/>

<br/><br/>

<img src="profile-summary-card-output/github_dark/0-profile-details.svg" width="49%" alt="Profile details card"/>
<img src="profile-summary-card-output/github_dark/3-stats.svg" width="49%" alt="Stats card"/>
<br/>
<img src="profile-summary-card-output/github_dark/1-repos-per-language.svg" width="49%" alt="Repos per language card"/>
<img src="profile-summary-card-output/github_dark/2-most-commit-language.svg" width="49%" alt="Most commit language card"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=abdelhakimgaferNetworkSec&theme=tokyonight&hide_border=true&background=0d1117&ring=00FF99&fire=00FF99&currStreakLabel=00FF99" alt="GitHub streak stats"/>

<br/><br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=abdelhakimgaferNetworkSec&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00FF99&line=00FF99&point=ffffff" alt="Contribution activity graph"/>

</div>

<img src="assets/divider.svg" width="100%"/>

## 🕓 Recent Activity

<!--START_SECTION:activity-->
<!-- This section is auto-populated by .github/workflows/recent-activity.yml
     after its first run. Do not edit between these markers by hand —
     it will be overwritten on the next scheduled update. -->
<!--END_SECTION:activity-->

<img src="assets/divider.svg" width="100%"/>

## 🏅 GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=abdelhakimgaferNetworkSec&theme=tokyonight&no-frame=true&column=4&margin-w=15&margin-h=15" alt="GitHub trophies"/>
</div>

<img src="assets/divider.svg" width="100%"/>

## 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/abdelhakimgaferNetworkSec/abdelhakimgaferNetworkSec/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake animation"/>
</div>

<img src="assets/divider.svg" width="100%"/>

## 🌐 More

<div align="center">

<a href="https://skyline.github.com/abdelhakimgaferNetworkSec/2026">
<img src="https://img.shields.io/badge/GitHub_Skyline-View_3D_Contributions-0f2027?style=for-the-badge&logo=github&logoColor=00FF99"/>
</a>
<img src="https://img.shields.io/badge/WakaTime-Not_yet_connected-0f2027?style=for-the-badge&logo=wakatime&logoColor=white"/>

</div>

<p align="center"><sub>GitHub Skyline generates a downloadable 3D model of your contribution graph at skyline.github.com — not an embeddable badge, so it's linked rather than inlined. The WakaTime badge is a placeholder: connect a WakaTime account and add a dedicated workflow to make it live (see <code>SETUP.md</code>).</sub></p>

<img src="assets/divider.svg" width="100%"/>

## 💬 Random Dev Quote

<div align="center">
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random developer quote"/>
</div>

<img src="assets/divider.svg" width="100%"/>

## 📫 Connect

<div align="center">

<a href="https://linkedin.com/in/abdel-hakim-gafer-tech"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/abdelhakimgaferNetworkSec"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="mailto:abdelhakimelazaly4@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<br/>

<div align="center">

### ⭐ Detecting, correlating, and containing — one enterprise-grade lab at a time ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=150&section=footer"/>

</div>
