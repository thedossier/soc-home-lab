# 🕵️‍♀️ SOC Home Lab

A home Security Operations Center (SOC) simulation built using **Wazuh**, **Filebeat**, and **Elasticsearch**.  
The lab collects and analyzes logs from Windows and Linux systems to detect security events such as privilege escalation, suspicious logins, and malware execution.

---

### 🧰 Features
- Wazuh manager for SIEM and rule-based detection  
- Log collection from multiple endpoints (Windows + Linux)  
- Custom detection rules and dashboards  
- Sample incident write-ups and investigation workflow

---

### 💡 Skills Demonstrated
- SIEM configuration and log analysis  
- Threat detection and rule customization  
- Incident response methodology  
- Linux and Windows log forensics

---

### 🔍 Example Incidents
- Privilege escalation detection (Event ID 4672)  
- Suspicious PowerShell command execution  
- Unauthorized login attempts from external IPs

---

### 🧾 Project Summary
This lab showcases hands-on experience in building and managing a SIEM environment.  
It demonstrates a security mindset, understanding of telemetry sources, and the ability to analyze and respond to alerts like a SOC analyst.

---

## 🧱 Virtualization Environment

This lab is fully virtualized to simulate a real-world IT environment.

**Platform:** VirtualBox (or VMware Workstation / Hyper-V)  
**Topology:**
- 🖥️ Windows Server (Domain Controller / File Server)
- 💻 Windows 10 Client(s)
- 🧰 Security Tools VM (Kali Linux, Wazuh, Security Onion, etc.)
- 🌐 pfSense (firewall + router)

**Networking:**  
- Internal NAT network for internet access  
- Host-only network for isolated lab traffic  
- Static IP addressing for critical systems  

This setup demonstrates understanding of:
- Virtual networking & isolation
- Resource allocation (CPU, memory, storage)
- Snapshot management
- System provisioning and configuration in a virtual environment

---
