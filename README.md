# SOC-Lab-Real-Time-Threat-Detection-with-Wazuh-SIEM
Built a Home SOC Lab using Wazuh SIEM to detect real-world attacks like sudo brute-force, SSH brute-force, and rogue user creation. Demonstrates log analysis, MITRE ATT&amp;CK mapping, and threat detection in a practical environment.
# 🛡️ Home SOC Lab: Real-Time Threat Detection with Wazuh SIEM

## 📌 Overview
This project showcases a fully functional **Home Security Operations Center (SOC)** built using **Wazuh SIEM**.  
The goal was to move beyond theoretical cybersecurity concepts and gain **hands-on experience in threat detection, log analysis, and incident response**.

By simulating real-world attacks, this lab demonstrates how security teams detect and respond to malicious activities using SIEM tools.

---

## 🏗️ Architecture

- **SIEM (Monitoring & Alerting):** Wazuh Manager  
- **Endpoint / Agent:** Kali Linux  
- **Attacker Machine:** Kali Linux  

---

## ⚙️ Tech Stack & Concepts

- Wazuh SIEM
- Kali Linux
- Log Analysis
- MITRE ATT&CK Framework
- File Integrity Monitoring (FIM)
- Active Response

---

## 🔬 Detection Labs

### 🔍 Lab 1: Insider Threat & Privilege Escalation
**Objective:** Detect unauthorized root access attempts  

- Simulated repeated failed `sudo` attempts  
- Triggered **Level 10 Critical Alerts**  
- Identified:
  - Source user  
  - Terminal session  

---

### 🌐 Lab 2: Network Reconnaissance & SSH Brute-Force
**Objective:** Detect scanning and unauthorized login attempts  

- Performed aggressive Nmap scans  
- Simulated SSH brute-force attack  

**Detection:**
- Level 5 Alerts → Recon activity  
- Level 10 Alerts → Multiple failed logins  


---

### 📁 Lab 3: Persistence & System Modification
**Objective:** Detect backdoor creation  

- Created hidden rogue user  
- Modified `/etc/passwd`  

**Detection:**
- Level 8 Alerts → New user creation  
- FIM Alerts → Critical file modification  

---

## 🎯 Key Learnings

- Practical experience with **SIEM dashboards & alert analysis**
- Mapping attacks to **MITRE ATT&CK techniques**
- Understanding **real-world attack footprints in logs**
- Difference between:
  - Passive Monitoring  
  - Active Threat Hunting  

---

## 🚀 Future Improvements

- Cloud-based SOC (AWS / Azure)
- Integration with Threat Intelligence feeds
- Automated Incident Response playbooks


---

## 📢 Connect With Me
If you found this project useful, feel free to connect and collaborate!
