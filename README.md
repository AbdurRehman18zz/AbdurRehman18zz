<!-- 
================================================================================
  SYSTEM_INIT: ADVANCED SOC & THREAT INTELLIGENCE DASHBOARD
  AUTHOR: ABD UR REHMAN | ROLE: BLUE TEAM / SECURITY OPERATIONS
  THEME: DARK CYBER / ENTERPRISE SOC
================================================================================ 
-->

<div align="center">

<!-- HERO BANNER -->
<img src="https://raw.githubusercontent.com/abdurrehman18zz/abdurrehman18zz/main/header.gif" onerror="this.src='https://i.pinimg.com/originals/e8/35/98/e8359850162580a6b7e682d33458a213.gif'" width="100%" height="220" style="object-fit: cover; border-radius: 12px; border: 1px solid #00D9FF;"/>

<br><br>

<!-- DYNAMIC CONSOLE TYPING -->
<a href="https://github.com/abdurrehman18zz">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&pause=1000&color=00D9FF&center=true&vCenter=true&width=900&lines=>_SOC_Analyst.exe+--execute;>_Initializing+Blue+Team+Defenses...;>_SIEM:+Wazuh+|+NIDS:+Suricata;>_Analyzing+NetFlow+&+Auth+Anomalies...;>_Optimizing+MTTR+and+RTO+Metrics...;>_Ready_For_Deployment." alt="Typing SVG"/>
</a>

<br>

<!-- COMMUNICATION & NETWORK BADGES -->
<a href="https://www.linkedin.com/in/abd-ur-rehman-12b7553b0/"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117"/></a>
<a href="mailto:abdurrehmanexex@gmail.com"><img src="https://img.shields.io/badge/SECURE_COMMS-EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117"/></a>
<a href="https://tryhackme.com/"><img src="https://img.shields.io/badge/TRAINING-TRYHACKME-B03A2E?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0D1117"/></a>
<a href="https://github.com/abdurrehman18zz"><img src="https://komarev.com/ghpvc/?username=abdurrehman18zz&label=PROFILE%20VIEWS&color=00D9FF&style=for-the-badge&labelColor=0D1117"/></a>

<br><br>

<!-- GITHUB TROPHIES (Dynamic) -->
<a href="https://github.com/abdurrehman18zz">
  <img src="https://github-profile-trophy.vercel.app/?username=abdurrehman18zz&theme=radical&no-frame=true&no-bg=true&margin-w=15&column=7" alt="GitHub Trophies" />
</a>

</div>

<br>

---

<h2 align="center"><code>[01] THE_ANALYST_PROFILE.md</code></h2>

<table>
<tr>
<td width="65%" valign="top">

### 🛡️ Defense in Depth Architect
I am a Cybersecurity professional engineering robust Blue Team environments. I move beyond textbook theory by constructing enterprise-grade virtual infrastructure, executing controlled detonations, and engineering precise SIEM detection logic. 

**Core Operational Focus:**
*   **Threat Detection & Analysis:** Investigating authentication log anomalies, calculating password entropy, and tracking incident response metrics.
*   **Security Architecture:** Designing SIEM log collection pipelines and configuring NetFlow traffic analysis via probes and collectors.
*   **IT Governance:** Applying risk management frameworks, structuring SLAs, and securing modern cloud architectures (IaC, FaaS).
*   **AI Integration:** Utilizing Gemini Advanced and locally/cloud-quantized open-weight models (Qwen, Dolphin) via Google Colab T4 GPUs for automated log parsing and script generation.

</td>
<td width="35%" align="center">

<img src="https://raw.githubusercontent.com/devSouvik/static-templates/main/assets/cybersecurity.gif" width="280" style="border-radius: 10px;"/>
<br><br>
<img src="https://img.shields.io/badge/CURRENT_STATUS-THREAT_HUNTING-00D9FF?style=for-the-badge&logo=target&logoColor=black"/>

</td>
</tr>
</table>

---

<h2 align="center"><code>[02] COMMAND_CENTER_HOMELAB.cfg</code></h2>

> **Hardware Backbone:** Operations run on a Lenovo ThinkBook 14 G6 IRL (Intel Core i7-1355U, DDR5 RAM, 1TB NVMe SSD). Analysis is conducted across a 2560x1080 ultrawide display for maximum dashboard visibility.

The environment utilizes a deeply segmented Host-Only virtual network to safely isolate malware detonation and threat emulation from the physical LAN.

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#0D1117', 'primaryTextColor': '#00D9FF', 'lineColor': '#00D9FF'} }}%%
graph TD
    subgraph "Centralized SOC Management (Ubuntu Server)"
        W[Wazuh Manager / Indexer]
        S[Suricata NIDS]
        W --- S
    end

    subgraph "Isolated Threat Detonation Zone"
        E1[Windows 11 Endpoint]
        E2[Ubuntu Desktop Endpoint]
    end

    %% Data flow arrows
    E1 -- "Sysmon Event ID 1 / Security Logs (Encrypted)" --> W
    E2 -- "Auditd / Syslog (Encrypted)" --> W
    E1 -. "Raw NetFlow Data via Host-Only Adapter" .-> S
    E2 -. "Raw NetFlow Data via Host-Only Adapter" .-> S
