# Ethical_Hacking_Task_02_Meghana- Network Scanning & Service Enumeration

## 📖 Project Overview

This repository contains the submission for **Ethical Hacking Task 02**, which focuses on **Network Scanning and Service Enumeration** using **Nmap**.

The objective of this task was to perform authorized network scanning on the local machine to identify open ports, running services, service versions, and operating system information. The exercise demonstrates how reconnaissance and enumeration help security professionals understand a system's attack surface while following ethical cybersecurity practices.

---

## 🎯 Objectives

The main objectives of this project were to:

- Install and configure Nmap.
- Verify the Nmap installation.
- Perform a basic scan on the local machine.
- Identify open TCP ports.
- Detect running network services.
- Perform service version detection.
- Identify the operating system using OS detection.
- Execute an aggressive scan for detailed information.
- Research the purpose of identified ports.
- Document all findings in a professional report.

---

## 💻 Target System

**Target:** Local Machine (localhost)

**Operating System Detected:** Microsoft Windows 10

**Scanning Tool:** Nmap 7.99

---

## 🛠️ Tools Used

- Nmap 7.99
- Windows Command Prompt
- Microsoft Word
- GitHub

---

## 📂 Repository Structure

```text
Ethical_Hacking_Task_02
│
├── README.md
├── Network_Scanning_Report.docx
├── Network_Scanning_Report.pdf
├── Research_Notes.docx
└── Screenshots
    ├── Nmap_Version.png
    ├── Localhost_Scan.png
    ├── Service_Version_Scan.png
    ├── OS_Detection.png
    └── Aggressive_Scan.png
```

---

## 🔍 Nmap Commands Executed

| Command | Purpose |
|---------|---------|
| `nmap --version` | Verify Nmap installation |
| `nmap localhost` | Scan localhost for open ports |
| `nmap -sV localhost` | Detect service versions |
| `nmap -O localhost` | Detect the operating system |
| `nmap -A localhost` | Perform an aggressive scan |

---

## 📊 Summary of Scan Results

The Nmap scan identified the following open ports on the local machine:

| Port | Service |
|------|---------|
| 135 | Microsoft RPC |
| 445 | Microsoft Directory Services (SMB) |
| 3306 | MySQL |
| 7070 | SSL/RealServer |
| 8090 | TCP Wrapped |

Additional findings from the aggressive scan included:

- Microsoft Windows 10 operating system detected.
- MySQL Server Version 8.0.46 identified.
- SSL-enabled service detected on port 7070.
- Additional service and host information gathered through Nmap's default scripts.

---

## 📚 Learning Outcomes

This project helped me gain practical knowledge of:

- Network scanning techniques
- Port scanning using Nmap
- Service enumeration
- Operating system detection
- Understanding common network services
- Interpreting scan results
- Security assessment fundamentals
- Professional technical documentation

---

## 🔐 Ethical Considerations

All scans performed during this project were conducted on my own local machine in a controlled environment. No unauthorized systems were scanned, and all activities were carried out strictly for educational and ethical learning purposes.

---

## 👩‍💻 Author

**Name:** Meghana S

**Internship:** Ethical Hacking Internship

**Task:** Task 02 – Network Scanning & Service Enumeration

---

## 📌 Acknowledgement

This project was completed as part of an Ethical Hacking Internship to develop practical skills in network scanning, service enumeration, system analysis, and professional cybersecurity documentation using industry-standard tools.
