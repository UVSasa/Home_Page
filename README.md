# 🛡️ Cybersecurity Home Lab - My First Security Repository

Welcome to my cybersecurity home lab! This repository documents my journey and projects as I build hands-on skills in cyber defense, monitoring, and offensive testing. The goal is to showcase real-world techniques and technologies used by SOC analysts, blue teamers, and ethical hackers.

---

## 🧠 What I’m Learning

- ✅ Setting up and configuring a SIEM (Security Information and Event Management) system using **Wazuh** and **ELK**
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

### 🔍 1. Log Monitoring with Wazuh
- Monitored failed login attempts and privilege escalation on Windows
- Added custom rules for Event ID 4672 and unusual registry changes

### 🛠️ 2. File Integrity Monitoring
- Tracked changes to sensitive system files
- Alerted on file creation and modification in user directories

### 🧬 3. Vulnerability Detection
- Scanned Windows endpoints for known CVEs
- Used Wazuh’s vulnerability-detector module

### ⚔️ 4. Offensive Testing with Kali Linux
- Simulated network sniffing, MITM, and DNS spoofing attacks
- Practiced safely in an offline lab setup

---
