# Wazuh Threat Hunting Project

This is a hands-on cybersecurity project where I deployed a Wazuh SIEM stack on AWS EC2 to monitor Linux and Windows systems. Tailscale was used to enable secure Zero Trust access to the environment from any location.

---

## 🔧 Technologies Used
- **Wazuh SIEM** (Ubuntu-based manager)
- **AWS EC2** (Ubuntu + Windows Server)
- **Tailscale** (Zero Trust VPN)
- **Kibana** (Log visualization)
- **File Integrity Monitoring**
- **EventChannel log collection**
- **Nmap** (Scan testing)
- **iptables** (Linux firewall)
- **PowerShell & Bash scripting**

---

## 📌 Project Overview
- Installed and configured Wazuh manager on Ubuntu EC2 instance
- Registered a Windows Server as an agent and enabled EventChannel monitoring
- Monitored login attempts, system changes, and integrity violations
- Used Tailscale to securely access Kibana dashboards remotely
- Ran Nmap scans to generate detection alerts
- Tuned firewall rules using iptables and AWS Security Groups
- Created and reviewed alerts in Kibana

---

## 📁 Files Included
- 
