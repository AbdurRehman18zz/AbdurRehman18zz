<!-- ========================================================= -->
<!--                      HERO SECTION                         -->
<!-- ========================================================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0D1117,35:111827,70:0E75B6,100:00D9FF&text=ABD%20UR%20REHMAN&fontSize=52&fontColor=FFFFFF&fontAlignY=38&desc=CYBERSECURITY%20%7C%20SOC%20%7C%20BLUE%20TEAM&descAlignY=62&descSize=20&animation=fadeIn" width="100%"/>

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=900&color=00D9FF&center=true&vCenter=true&width=900&lines=Aspiring+SOC+Analyst+%F0%9F%9B%A1%EF%B8%8F;Cybersecurity+Enthusiast+%F0%9F%94%90;Security+Monitoring+%26+Threat+Detection;Blue+Team+%7C+SIEM+%7C+Incident+Response;Learning+%E2%86%92+Building+%E2%86%92+Detecting+%E2%86%92+Defending" alt="Typing SVG"/>

<br><br>

<!-- Badges -->
<a href="https://github.com/abdurrehman18zz">
  <img src="https://komarev.com/ghpvc/?username=abdurrehman18zz&label=PROFILE%20VIEWS&color=00D9FF&style=for-the-badge" alt="Profile Views"/>
</a>
<a href="https://github.com/abdurrehman18zz?tab=followers">
  <img src="https://img.shields.io/github/followers/abdurrehman18zz?label=FOLLOWERS&style=for-the-badge&logo=github&logoColor=white&color=111827" alt="Followers"/>
</a>
<a href="https://github.com/abdurrehman18zz?tab=repositories">
  <img src="https://img.shields.io/github/stars/abdurrehman18zz?label=STARS&style=for-the-badge&logo=github&logoColor=white&color=111827" alt="GitHub Stars"/>
</a>

<br><br>

<!-- Socials -->
<a href="https://www.linkedin.com/in/abd-ur-rehman-12b7553b0/">
  <img src="https://img.shields.io/badge/LinkedIn-00D9FF?style=for-the-badge&logo=linkedin&logoColor=111827"/>
</a>
<a href="mailto:abdurrehmanexex@gmail.com">
  <img src="https://img.shields.io/badge/Email_Me-0E75B6?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://tryhackme.com/p/yourusername">
  <img src="https://img.shields.io/badge/TryHackMe-111827?style=for-the-badge&logo=tryhackme&logoColor=white"/>
</a>

</div>

---

<!-- ========================================================= -->
<!--                       EXECUTIVE SUMMARY                   -->
<!-- ========================================================= -->

<h2 align="center">🕵️‍♂️ Executive Summary</h2>

<div align="center">
  <p>
    I am a Computer Science student and an aspiring <b>SOC Analyst</b> focused on <b>Blue Team operations, threat detection, and security monitoring</b>. I believe in hands-on learning: stepping away from textbooks to build real-world enterprise architectures, generate simulated attacks, and hunt for the resulting telemetry in SIEM dashboards.
  </p>
  <p>
    <i>"Learn the concept → Build the lab → Generate the activity → Investigate the logs → Detect the threat → Document the findings"</i>
  </p>
</div>

---

<!-- ========================================================= -->
<!--                    TECHNICAL SKILLS                       -->
<!-- ========================================================= -->

<h2 align="center">⚙️ Technical Arsenal</h2>

<div align="center">

**SIEM & Security Monitoring**<br>
<img src="https://img.shields.io/badge/Wazuh-00D9FF?style=for-the-badge&logo=wazuh&logoColor=111827" />
<img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" />
<img src="https://img.shields.io/badge/Suricata-0E75B6?style=for-the-badge&logo=suricata&logoColor=white" />
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />

<br>

**Operating Systems & Cloud**<br>
<img src="https://img.shields.io/badge/Windows_11-0078D4?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/Windows_Server-0078D4?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />

<br>

**Networking & Scripting**<br>
<img src="https://img.shields.io/badge/TCP/IP_&_OSI-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/Bash_Scripting-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />

</div>

---

<!-- ========================================================= -->
<!--                    THE SOC HOMELAB                        -->
<!-- ========================================================= -->

<h2 align="center">🔬 Enterprise SOC Homelab</h2>

<table>
<tr>
<td width="55%">

### Architecture Overview
My custom-built Security Operations Center (SOC) lab, designed to simulate an enterprise environment. It allows me to detonate malware safely, track lateral movement, and write custom detection rules.

*   **Central Brain:** Ubuntu Server hosting **Wazuh** (SIEM/XDR) and **Suricata** (NIDS).
*   **Endpoints:** Windows 11 and Ubuntu Desktop forwarding telemetry.
*   **Networking:** Host-Only adapter for complete isolation, allowing safe execution of real threats.
*   **Next Steps:** Integrating pfSense for network segmentation and Sysmon for deep process tracking.

</td>
<td width="45%">
<div align="center">
<img src="https://raw.githubusercontent.com/devSouvik/static-templates/main/assets/cybersecurity.gif" width="100%" alt="Cybersecurity GIF"/>
</div>
</td>
</tr>
</table>

<div align="center">

```text
                         ┌─────────────────────────┐
                         │       SOC SERVER        │
                         │                         │
                         │     Ubuntu Server       │
                         │                         │
                         │  ┌───────────────────┐  │
                         │  │       WAZUH       │  │
                         │  │ SIEM / Monitoring │  │
                         │  └───────────────────┘  │
                         │                         │
                         │  ┌───────────────────┐  │
                         │  │     SURICATA      │  │
                         │  │ Network Detection │  │
                         │  └───────────────────┘  │
                         └────────────┬────────────┘
                                      │
                       Logs / Events / Network Data
                                      │
                 ┌────────────────────┴────────────────────┐
                 │                                         │
        ┌────────▼────────┐                       ┌────────▼────────┐
        │   WINDOWS 11    │                       │ UBUNTU DESKTOP  │
        │    ENDPOINT     │                       │    ENDPOINT     │
        │                 │                       │                 │
        │ Windows Events  │                       │ Linux Logs      │
        │ Security Events │                       │ System Activity │
        └─────────────────┘                       └─────────────────┘
