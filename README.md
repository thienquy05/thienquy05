<h1 align="center">Thien Quy Pham</h1>

<p align="center">
  <b>Cybersecurity &amp; AI Security</b><br>
  B.S. Computer Science · University of Toledo · GPA 3.6 · Graduating Dec 2027
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Seeking-Summer%202027%20Cybersecurity%20Internship-2EA043?style=for-the-badge" alt="Seeking Summer 2027 cybersecurity internship">
</p>

<p align="center">
  <a href="https://thienquypham.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-1F3864?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/thienquypham/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ThienQuy.Pham@rockets.utoledo.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <a href="#-at-a-glance">At a glance</a> ·
  <a href="#-experience">Experience</a> ·
  <a href="#-featured-projects">Projects</a> ·
  <a href="#-skills">Skills</a> ·
  <a href="#-education--certifications">Education</a> ·
  <a href="#-contact">Contact</a>
</p>

---

## 📊 At a glance

| 🖥️ **1,000+** | 🚨 **15+** | 🏫 **250+** | ⚡ **< 5 ms** | 🎯 **+10 pts** |
|:---:|:---:|:---:|:---:|:---:|
| Windows & macOS endpoints managed (AD + Intune) | Security incidents handled in 4 months | Classrooms & offices supported (Tier 2) | Prompt-injection block time, down from 15-20 s | Block-rate gain in LLM red-team, zero false positives |

**What I bring**

- **Hands-on defense:** triage alerts, isolate malware-infected devices, patch and enforce compliance at university scale.
- **AI security:** red-teamed an LLM phishing detector with 41 real attack payloads, then shipped the fix.
- **Builder:** full-stack and Python projects, from a CAPTCHA-solving model to a firewall for AI agents.
- **Reliable teammate:** escalation notes written so the next technician can reproduce the fix.

---

## 💼 Experience

### IT System Administrator · University of Toledo
`Jan 2026 – Present`
- Triage security alerts and enforce device compliance across **1,000+ Windows and macOS endpoints** via Active Directory and Microsoft Intune.
- Responded to **15+ security incidents in four months**, including remediating unpatched Windows 10 endpoints and isolating 2 malware-infected devices.
- Own the endpoint lifecycle (imaging, deployment, patching, hardware refresh) and give Tier 2 support to **250+ classrooms and offices**.

### Undergraduate Research Assistant · University of Toledo
`Dec 2025 – Present`
- Build Python/OpenCV tracking and behavior-state analysis for zebrafish Novel Tank Test footage.
- Label trial data and run model evaluation workflows.

### IT Support Technician · University of Toledo
`Dec 2025 – May 2026`
- Resolved **10-15 tickets/week** through UToledoHelp, with escalation notes written so the next technician can reproduce the fix.

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [AEGIS (Injection Arena)](https://github.com/MakeUC2026/AEGIS)
*MakeUC 2026 · 4-person team*

A game that teaches how AI agents get tricked: students attack chatbots behind a rule-based agent firewall that allows, denies, holds for review or diverts each message and tool call. A teach-back quiz and a teacher dashboard show where a class struggles.

**My part:** designed the firewall workflow, built the admin and intelligence workers (event processing, drafted rule candidates), redesigned the admin and classroom console.

`Python` `FastAPI` `Next.js` `PostgreSQL` `Gemini`

</td>
<td width="50%" valign="top">

### 🎣 [Sentra](https://github.com/Phishing-Detection-Team/fraudify) (repo: fraudify)
*AI phishing detection · 4-person team*

- Regex pre-flight filter blocks jailbreak and prompt-injection payloads before they reach the LLM: **under 5 ms instead of 15-20 s**.
- Red-teamed with 41 real payloads, patched the gap, and raised the block rate **10 points with zero false positives**.
- Closed a CSS-hidden-content injection in the Gmail/Outlook extension, and applied NIST CSF data-integrity practices in PostgreSQL (bcrypt, 20 check constraints, 15 validators).

`Python` `Flask` `PostgreSQL` `TypeScript`

</td>
</tr>
</table>

| Project | What it does | Stack |
|---|---|---|
| [**vuln-scanner**](https://github.com/thienquy05/vuln-scanner) | Multithreaded TCP port scanner with banner grabbing. Saves results to a text file and a SQLite database. | `Python` `SQLite` |
| [**BreakingModernCaptcha**](https://github.com/thienquy05/BreakingModernCaptcha) | Web app where a TensorFlow/Keras model finds the matching tiles in a 3x3 "select all images with..." CAPTCHA grid. | `Python` `Flask` `TensorFlow` |
| [**phishing-awareness-pro**](https://github.com/thienquy05/phishing-awareness-pro) ([live](https://clicksmart.vercel.app)) | Shows what a single click exposes (IP, timestamp), then emails an educational warning. Stateless, rate-limited to 5 requests/min and 20/day per IP. | `TypeScript` `Next.js` `Flask` |
| [**Portfolio**](https://github.com/thienquy05/Portfolio) ([live](https://thienquypham.vercel.app/)) | My personal site. | `TypeScript` |

---

## 🧰 Skills

**Cybersecurity**<br>
![Incident Response](https://img.shields.io/badge/Incident%20Response-B31B1B?style=flat-square)
![Threat Analysis](https://img.shields.io/badge/Threat%20Analysis-B31B1B?style=flat-square)
![Malware Containment](https://img.shields.io/badge/Malware%20Containment-B31B1B?style=flat-square)
![Vulnerability & Patch Management](https://img.shields.io/badge/Vuln%20%26%20Patch%20Mgmt-B31B1B?style=flat-square)
![Endpoint Security](https://img.shields.io/badge/Endpoint%20Security-B31B1B?style=flat-square)
![NIST CSF](https://img.shields.io/badge/NIST%20CSF-B31B1B?style=flat-square)
![OSINT](https://img.shields.io/badge/OSINT-B31B1B?style=flat-square)
![Network Segmentation](https://img.shields.io/badge/Network%20Segmentation-B31B1B?style=flat-square)

**AI security**<br>
![Prompt Injection Defense](https://img.shields.io/badge/Prompt%20Injection%20Defense-6F42C1?style=flat-square)
![Jailbreak Red-Teaming](https://img.shields.io/badge/Jailbreak%20Red--Teaming-6F42C1?style=flat-square)
![Model Evaluation](https://img.shields.io/badge/Model%20Evaluation-6F42C1?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-6F42C1?style=flat-square&logo=opencv&logoColor=white)

**Systems**<br>
![Active Directory](https://img.shields.io/badge/Active%20Directory-0078D4?style=flat-square)
![Microsoft Intune](https://img.shields.io/badge/Microsoft%20Intune-0078D4?style=flat-square)
![PowerShell](https://img.shields.io/badge/PowerShell-0078D4?style=flat-square&logo=powershell&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-0078D4?style=flat-square&logo=apple&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-0078D4?style=flat-square&logo=linux&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-0078D4?style=flat-square&logo=vmware&logoColor=white)

**Languages & tools**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Labs**<br>
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)
![HackTheBox](https://img.shields.io/badge/HackTheBox-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)

---

## 🎓 Education & Certifications

| | |
|---|---|
| **B.S. Computer Science**, University of Toledo | GPA 3.6 · Expected Dec 2027 |
| **Google Cybersecurity Professional Certificate**, Coursera | Completed Oct 2025 |
| **CompTIA Security+** | In progress |

---

## 📬 Contact

<p align="center">
  <b>Open to Summer 2027 cybersecurity internships.</b><br>
  <a href="mailto:ThienQuy.Pham@rockets.utoledo.edu">ThienQuy.Pham@rockets.utoledo.edu</a> ·
  <a href="https://www.linkedin.com/in/thienquypham/">LinkedIn</a> ·
  <a href="https://thienquypham.vercel.app/">Portfolio</a>
</p>
