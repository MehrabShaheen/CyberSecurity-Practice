# 🛡️ Cybersecurity Portfolio — Practical Labs & Analysis Reports

> A collection of hands-on cybersecurity labs, deployment reports, 
> and attack analysis projects completed as part of independent 
> security research and self-directed learning.

---

## 👤 About

**Name:** Mehrab Shaheen   
**Focus Areas:** SOC Operations | Threat Intelligence | SIEM | 
Endpoint Detection | Attack Analysis  

---

## 📁 Repository Structure
📦 Cybersecurity-Portfolio
├── 📂 01-MISP
│   └── CTI Platform(MISP).pdf
├── 📂 02-OpenCTI
│   └── CTI--OpenCTI(1).pdf
├── 📂 Attack-Simulations-in-SOC
│   ├── Multi-Stage Attack Analysis.pdf
│   └── PowerShell-Based Multi-Stage Attack.pdf
├── 📂 Home-SOC-Deployment
│   └── Home SOC Lab Deployment Report.pdf
├── 📂 Phishing-Email-Analysis
│   └── Phishing Email Analysis.pdf
└── 📂 SIEM-Splunk
└── SIEM Tool(Splunk).pdf

---

## 📄 Projects Overview

### 🔵 1. Home SOC Lab — Deployment & Configuration
**Folder:** `Home-SOC-Deployment`

A complete virtual Security Operations Center built entirely on 
VMware Workstation Pro with 16 GB RAM on a Windows 11 host.

**What was deployed:**
- pfSense 2.7.x — Firewall, Router, Inter-subnet Gateway
- Suricata IDS — Network intrusion detection on pfSense
- Wazuh 4.x — SIEM/EDR (self-hosted, all-in-one deployment)
- Sysmon — Endpoint telemetry on Windows 10
- MISP — Threat intelligence & IOC management (Docker)
- OpenCTI — Threat intelligence correlation (Docker)
- DVWA — Vulnerable web application target (Docker)
- Kali Linux — Attacker machine in isolated subnet
- Splunk Cloud — Log analysis exploration 

**Key Skills:** Network segmentation | Agent enrollment | 
IDS configuration | Threat intel integration | Log analysis

---

### 🟣 2. CTI Platform — MISP
**Folder:** `01-MISP`

Hands-on exploration of MISP (Malware Information Sharing 
Platform) for threat intelligence management.

**Covered:**
- IOC creation and management
- Custom threat event scenarios
- TLP tagging and attribute classification
- MITRE ATT&CK mapping via Galaxy clusters
- OSINT feed ingestion and management
- MISP–OpenCTI integration

---

### 🟣 3. CTI Platform — OpenCTI
**Folder:** `02-OpenCTI`

Deployment and exploration of OpenCTI for threat intelligence 
correlation and visualization.

**Covered:**
- Docker Compose deployment
- MISP connector configuration
- Knowledge graph visualization
- Indicator and relationship analysis
- ATT&CK technique mapping

---

### 🔴 4. Attack Simulations in SOC
**Folder:** `Attack-Simulations-in-SOC`

Analysis of multi-stage attack scenarios within a SOC environment.

**Reports include:**
- Multi-Stage Attack Analysis using SOC tools
- PowerShell-Based Multi-Stage Attack analysis

**Key Skills:** Attack chain analysis | SOC detection workflow | 
PowerShell threat detection | Alert correlation

---

### 🟡 5. Phishing Email Analysis
**Folder:** `Phishing-Email-Analysis`

Practical analysis of phishing email samples — examining headers, 
payloads, indicators of compromise, and detection techniques.

**Covered:**
- Email header analysis
- IOC extraction from phishing samples
- Phishing detection methodology
- Reporting and documentation

---

### 🟢 6. SIEM Tool — Splunk
**Folder:** `SIEM-Splunk`

Hands-on exploration of Splunk as a SIEM tool using sample 
security log datasets.

**Covered:**
- Data ingestion and index management
- SPL (Search Processing Language) queries
- Dashboard and visualization creation
- Log source analysis and filtering

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| Virtualization | VMware Workstation Pro |
| Firewall / Network | pfSense, Suricata IDS |
| SIEM / EDR | Wazuh, Splunk |
| Threat Intelligence | MISP, OpenCTI |
| Endpoint | Sysmon, Wazuh Agent |
| Attack / Vuln Testing | Kali Linux, DVWA |
| Containerization | Docker, Docker Compose |
| OS | Windows 10/11, Ubuntu 20.04, Kali Linux |

---

## 📌 Note

All projects in this repository are independently completed 
for learning and portfolio purposes. No unauthorized systems 
were targeted. All attack simulations were performed within 
isolated lab environments.

