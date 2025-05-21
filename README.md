# 🛡️ Cybersecurity Home Lab - My First Security Repository

Welcome to my cybersecurity home lab! This repository documents my journey and projects as I build hands-on skills in cyber defense, monitoring, and offensive testing. The goal is to showcase real-world techniques and technologies used by SOC analysts, blue teamers, and ethical hackers.

---

## 🧠 What I’m Learning

- ✅ Setting up and configuring a SIEM/EDR (Security Information and Event Management/Endpoint Detection and Response) system using **Wazuh** and **ELK**
- ✅ Monitoring endpoint logs from Windows and Linux systems
- ✅ Performing file integrity monitoring (FIM), vulnerability detection, and user activity tracking
- ✅ Running MITM (Man-in-the-Middle) attacks safely in an offline lab using **Kali Linux** and **Ettercap**
- ✅ Practicing with firewalls, IDS/IPS (e.g., **Snort**), and basic malware detection
- ✅ Creating custom detection rules and alerts for suspicious activity

---

## 🧪 Lab Environment

| Component            | Description                                     |
|---------------------|-------------------------------------------------|
| **Host OS**         | Windows / Linux / macOS (varies)                |
| **VM Platform**     | VMware Fusion / Workstation                     |
| **SIEM Tool**       | Wazuh                                           |
| **Attack Box**      | Kali Linux VM                                   |
| **Victim Machine**  | Windows 10 / Windows 11 VM                      |
| **Firewall**        | pfSense or basic iptables for filtering traffic |
| **Networking**      | Isolated router, simulated traffic, MITM setup  |

---

## 📊 Projects & Experiments

### 🔍 1. Wazuh : [🔍 Wazuh EDR Lab](https://github.com/UVSasa/Wazuh-Siem)
- Log Monitoring with Wazuh EDR
- Vulnerability Detection
- File Integrity Monitoring

🧪 Projects & Experiments

⚙️ 1. Wazuh Lab Setup (SIEM & EDR Foundations)
	•	Set up the Wazuh Manager and connected Windows/macOS agents
	•	Verified agent communication and alert generation
	•	Tuned default rules to reduce noise from legitimate system activity
	•	Installed and configured Sysmon for enriched Windows telemetry
	•	Created custom rules in local_rules.xml

⸻

🛡️ 2. Network Defense (Blue Team)
	•	Log Monitoring: Tracked failed logins, privilege escalations (e.g., Event ID 4672), and unusual process activity
	•	Vulnerability Detection: Used Wazuh’s vulnerability-detector to identify known CVEs on Windows endpoints
	•	File Integrity Monitoring: Monitored system files and user directories for suspicious changes or DLL injections
	•	Rule Tuning: Differentiated between benign system events and potential attacks (e.g., analyzing svchost and DLL creation)

⸻

⚔️ 3. Offensive Security (Red Team)
	•	Reconnaissance & Information Gathering: Identified hosts, services, and open ports within the offline lab
	•	Vulnerability Scanning & Analysis: Scanned targets using tools like Nmap and Nikto to enumerate weaknesses
	•	Exploitation: Simulated attacks to test defensive visibility (e.g., MITM, DNS spoofing)
	•	Web Application Attacks: (Coming soon) — Will simulate OWASP Top 10-style attacks on a local vulnerable web app


### 🧬 4. Forensics
- Coming Soon

---
