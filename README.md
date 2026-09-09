<!-- 
================================================================================
  SECURITY OPERATIONS CENTER (SOC) - ANALYST PROFILE 
  Status: SECURE | Theme: CYBER-BLUE | Layout: RESPONSIVE
================================================================================ 
-->

<div align="center">

<!-- ANIMATED TERMINAL HEADER -->
<a href="https://github.com/abdurrehman18zz">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00D9FF&center=true&vCenter=true&width=800&lines=>_SOC+Analyst+|+Blue+Team+Specialist;>_Identity_Verified:+Abd+Ur+Rehman;>_Status:+Monitoring+Network+Telemetry...;>_Cert_Path:+CompTIA+Security%2B;>_System:+Wazuh+XDR+|+Suricata+NIDS" alt="Typing SVG"/>
</a>

<br><br>

<!-- DYNAMIC GITHUB SHIELDS -->
<a href="https://www.linkedin.com/in/abd-ur-rehman-12b7553b0/"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000000"/></a>
<a href="mailto:abdurrehmanexex@gmail.com"><img src="https://img.shields.io/badge/SECURE_COMMS-EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000000"/></a>
<a href="https://tryhackme.com/"><img src="https://img.shields.io/badge/TRAINING-TRYHACKME-B03A2E?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=000000"/></a>
<a href="https://github.com/abdurrehman18zz"><img src="https://komarev.com/ghpvc/?username=abdurrehman18zz&label=PROFILE%20VIEWS&color=00D9FF&style=for-the-badge&labelColor=000000"/></a>

<br><br>

</div>

---

<h2 align="center"><code>[01] EXECUTIVE_SUMMARY.txt</code></h2>

<p align="center">
  <b>Cybersecurity student and aspiring SOC Analyst specializing in defense-in-depth architecture.</b><br> 
  My methodology bridges the gap between theory and execution: I build enterprise-grade virtual environments, engineer simulated attacks, analyze the resulting network telemetry, and write custom SIEM detections to hunt threats. Currently analyzing incident response metrics (MTTR/RTO), authentication log anomalies, and password entropy calculations in preparation for the <b>CompTIA Security+</b> certification.
</p>

---

<h2 align="center"><code>[02] TECHNICAL_ARSENAL.exe</code></h2>

<div align="center">

| **SIEM & SECURITY MONITORING** | **NETWORK & INFRASTRUCTURE** | **SYSTEMS & AUTOMATION** |
| :---: | :---: | :---: |
| <img src="https://img.shields.io/badge/Wazuh_XDR-00D9FF?style=for-the-badge&logo=wazuh&logoColor=black"/> | <img src="https://img.shields.io/badge/Suricata_NIDS-EF3B2D?style=for-the-badge&logo=suricata&logoColor=white"/> | <img src="https://img.shields.io/badge/Ubuntu_Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/> |
| <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white"/> | <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white"/> | <img src="https://img.shields.io/badge/Windows_11-0078D6?style=for-the-badge&logo=windows&logoColor=white"/> |
| <img src="https://img.shields.io/badge/Event_Viewer-0052CC?style=for-the-badge&logo=microsoft&logoColor=white"/> | <img src="https://img.shields.io/badge/Host--Only_Nets-4B32C3?style=for-the-badge&logo=cisco&logoColor=white"/> | <img src="https://img.shields.io/badge/Python_Scripting-3776AB?style=for-the-badge&logo=python&logoColor=white"/> |

</div>

<br>

---

<h2 align="center"><code>[03] ENTERPRISE_SOC_HOMELAB.cfg</code></h2>

> **Infrastructure Engine:** Powered by a Lenovo ThinkBook 14 G6 IRL (Intel Core i7-1355U, DDR5, 1TB NVMe, Ultrawide 2560x1080 display). This architecture provides the compute necessary to run highly isolated, concurrent virtual environments without performance degradation.

```text
 ╔══════════════════════════════════════════════════════════════════════════╗
 ║                     CENTRALIZED SOC COMMAND CENTER                       ║
 ║                        [ Ubuntu Server 22.04 ]                           ║
 ║                                                                          ║
 ║       ┌────────────────────────┐            ┌────────────────────────┐   ║
 ║       │      WAZUH SIEM        │            │     SURICATA NIDS      │   ║
 ║       │  (Log Aggregation &    │            │ (NetFlow Analysis &    │   ║
 ║       │   Alert Generation)    │            │  Signature Matching)   │   ║
 ║       └───────────┬────────────┘            └────────────┬───────────┘   ║
 ╚═══════════════════│══════════════════════════════════════│═══════════════╝
                     │                                      │
                     │  <-- Encrypted TLS Telemetry -->     │ 
                     │                                      │
 ╔═══════════════════▼══════════════════════════════════════▼═══════════════╗
 ║               SECURE HOST-ONLY ISOLATED NETWORK ADAPTER                  ║
 ╚═══════════════════╦══════════════════════════════════════╦═══════════════╝
                     │                                      │
           ┌─────────┴─────────┐                  ┌─────────┴─────────┐
           │    ENDPOINT 01    │                  │    ENDPOINT 02    │
           │                   │                  │                   │
           │    Windows 11     │                  │  Ubuntu Desktop   │
           │                   │                  │                   │
           │  [Sysmon Deployed]│                  │ [Auditd Deployed] │
           └───────────────────┘                  └───────────────────┘
