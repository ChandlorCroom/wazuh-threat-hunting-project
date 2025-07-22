# Wazuh Threat Hunting Project

This is a hands-on cybersecurity project where I deployed a Wazuh SIEM stack on AWS EC2 to monitor both Linux and Windows systems. Tailscale was used to provide secure, Zero Trust remote access to the environment.

---

## 🔧 Technologies Used
- **Wazuh SIEM** (Ubuntu-based manager)
- **AWS EC2** (Ubuntu & Windows Server)
- **Tailscale** (Zero Trust VPN mesh)
- **Kibana** (Log visualization)
- **File Integrity Monitoring**
- **EventChannel log collection**
- **Nmap** (Scan simulation for alerting)
- **iptables** (Linux firewall hardening)
- **PowerShell & Bash scripting**

---

## 📌 Project Overview
- Installed and configured Wazuh Manager on an Ubuntu EC2 instance
- Registered both Windows and Linux agents, enabling EventChannel logging
- Monitored failed logon attempts, system changes, and file integrity events
- Used Tailscale to securely access the SIEM and dashboards remotely
- Simulated scanning behavior with Nmap to test alert generation
- Tuned firewall and security group rules using `iptables` and AWS settings
- Investigated and reviewed alerts through Kibana visualizations

---

## 📁 Files Included
- `topology.png` – Project architecture layout
- `wazuh-dashboard.png` – Agent dashboard (redacted)
- `failed-logon-BLUR.jpg` – Logon alert visibility (redacted)
