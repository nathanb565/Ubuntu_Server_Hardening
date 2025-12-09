# Ubuntu_Server_Hardening
Ubuntu server hardening project
# Ubuntu Server Hardening Project

## 📌 Overview
This project demonstrates how to identify and remediate insecure configurations on an Ubuntu Server.  
The focus was on **SSH security hardening** and **firewall configuration** to reduce the attack surface.

## 🎯 Objectives
- Detect insecure SSH settings (root login enabled, password authentication allowed).
- Audit the system using **Lynis** to identify vulnerabilities.
- Remediate by enforcing **key-based authentication** and disabling root/password logins.
- Enable and configure **UFW firewall** to restrict network access.
- Validate improvements with repeated scans and audits.

## 🛠️ Tools & Technologies
- **Nmap** – Port scanning and service detection.
- **Lynis** – System auditing and hardening index.
- **Ubuntu Server** – Target environment.
- **SSH** – Secure shell access.
- **UFW** – Firewall configuration.
- **VirtualBox** – Lab virtualization environment.
