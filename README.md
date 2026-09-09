<!-- 
=======================================================================
  CYBERSECURITY COMMAND CENTER DASHBOARD (README.md)
  THEME: NEON CYAN / DARK MODE / TERMINAL
======================================================================= 
-->

<div align="center">

<img src="https://raw.githubusercontent.com/abdurrehman18zz/abdurrehman18zz/main/header.gif" onerror="this.src='https://i.pinimg.com/originals/99/3a/0d/993a0d513e9a7e6b7260cb0ce08ee622.gif'" width="100%" height="200" style="object-fit: cover; border-radius: 10px;"/>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00FFFF&center=true&vCenter=true&width=800&lines=>_Initializing+Security+Operations+Center...;>_Establishing+Secure+Connection...;>_Identity_Verified:+Abd+Ur+Rehman;>_Role:+Blue+Team+|+SOC+Analyst;>_Status:+Monitoring+Network+Telemetry..." alt="Typing SVG"/>

<br>

[![LinkedIn](https://img.shields.io/badge/CONNECTION-LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abd-ur-rehman-12b7553b0/)
[![Email](https://img.shields.io/badge/SECURE_COMMS-EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdurrehmanexex@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TRAINING-TRYHACKME-B03A2E?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/)
[![Views](https://komarev.com/ghpvc/?username=abdurrehman18zz&label=DASHBOARD_VIEWS&color=00FFFF&style=for-the-badge)](https://github.com/abdurrehman18zz)

</div>

<br>

---

<table align="center" width="100%">
<tr>
<td width="55%" valign="top">

### <code>>_ whoami</code>

I am a Cybersecurity and Security Operations professional architecting defense-in-depth strategies. My methodology moves beyond theory into practical application: building environments, engineering attacks, analyzing the resulting NetFlow and telemetry, and engineering SIEM detections. 

Currently preparing for the **CompTIA Security+** examination and actively analyzing incident response metrics like MTTR vs. RTO, authentication log anomalies, and password entropy calculations.

### <code>>_ execution_metrics.sh</code>

*   **Primary Directive:** SOC Analysis, SIEM Engineering, Incident Response.
*   **Current Operation:** Engineering custom Wazuh detection rules for living-off-the-land (LotL) execution.
*   **Architecture Focus:** SOAR integration, NetFlow traffic analysis via Suricata, and SIEM log collection architectures.

</td>
<td width="45%" align="center">

<img src="https://github-readme-stats.vercel.app/api?username=abdurrehman18zz&show_icons=true&bg_color=00000000&title_color=00FFFF&text_color=FFFFFF&icon_color=00FFFF&hide_border=true&hide_rank=false" alt="GitHub Stats" width="100%"/>

</td>
</tr>
</table>

---

<h3 align="center"><code>>_ ARSENAL_AND_TOOLS.exe</code></h3>

<div align="center">

| **SIEM & Monitoring** | **Network & EDR** | **Infrastructure & OS** |
| :--- | :--- | :--- |
| <img src="https://img.shields.io/badge/Wazuh-00FFFF?style=for-the-badge&logo=wazuh&logoColor=black"/> <br> <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white"/> | <img src="https://img.shields.io/badge/Suricata-EF3B2D?style=for-the-badge&logo=suricata&logoColor=white"/> <br> <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white"/> | <img src="https://img.shields.io/badge/Ubuntu_Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/> <br> <img src="https://img.shields.io/badge/Windows_11-0078D6?style=for-the-badge&logo=windows&logoColor=white"/> |

</div>

---

<h3 align="center"><code>>_ ENTERPRISE_SOC_HOMELAB.cfg</code></h3>

<table align="center" width="100%">
<tr>
<td width="40%" valign="top">

#### **Hardware & Infrastructure**
*   **Host Engine:** Lenovo ThinkBook 14 G6 IRL
*   **Compute:** Intel Core i7-1355U, DDR5 RAM
*   **Storage:** 1TB NVMe SSD + External HDD
*   **Monitoring Array:** 2560x1080 Ultrawide Display
*   **Network Fabric:** Virtualized Host-Only Isolation Adapter

#### **Operational Capabilities**
*   **Endpoint Telemetry:** Ingesting Sysmon/Windows Event Logs and Linux system logs into Wazuh.
*   **NIDS:** Suricata sniffing host-only traffic for signature matching.
*   **Threat Hunting:** Querying SIEM dashboards for log anomalies and calculating response metrics.

</td>
<td width="60%" align="center">

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#0d1117', 'primaryTextColor': '#00FFFF', 'primaryBorderColor': '#00FFFF', 'lineColor': '#00FFFF', 'secondaryColor': '#111827', 'tertiaryColor': '#1f2937'} }}%%
graph TD
    subgraph SOC_Command_Center
        S1[Ubuntu Server]
        W[Wazuh SIEM]
        SU[Suricata NIDS]
        S1 --> W
        S1 --> SU
    end

    subgraph Isolated_Threat_Network
        E1[Windows 11 Endpoint]
        E2[Ubuntu Desktop Endpoint]
    end

    E1 -- Sysmon / Event IDs --> W
    E2 -- Syslog / Auditd --> W
    E1 -. Host-Only Adapter Traffic .-> SU
    E2 -. Host-Only Adapter Traffic .-> SU
