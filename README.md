# Cybersecurity Foundation Lab Documentation: Kali & Metasploitable2

## Project Overview

This repository documents the setup and initial hands-on tasks for a foundational cybersecurity home lab, built using Kali Linux (attacker) and Metasploitable2 (target) on a VirtualBox Host-Only network. This project validates skills in Linux fundamentals, networking, cryptography, and essential penetration testing tools.

## Deliverables Status

| Deliverable | Status | Location |
| :--- | :--- | :--- |
| **Lab Setup Report** | **COMPLETED** | `documentation/lab-setup-report.md` |
| **Linux Cheat-sheet** | **COMPLETED** | `notes/linux-cheat-sheet.md` |
| **Networking Basics Notes** | **COMPLETED** | `notes/networking-basics.md` |
| **Cryptography Basics Notes** | **COMPLETED** | `notes/cryptography-basics.md` |
| **5-min Video Walkthrough** | **COMPLETED** | **[INSERT YOUTUBE/DRIVE LINK HERE]** |

## Lab Environment Details

* **Attacker OS:** Kali Linux (VM)
* **Target OS:** Metasploitable2 (VM)
* **Network Type:** VirtualBox Host-Only Adapter (Isolated Network)

---

## Tool Familiarization Summary (Task 6)

| Tool | Purpose | Proof |
| :--- | :--- | :--- |
| **Nmap** | Host Discovery / Port Scanning | Successfully identified multiple open services (e.g., FTP, Telnet, HTTP) on the target. |
| **Wireshark** | Packet Analysis | Successfully captured ICMP (ping) traffic between Kali and Metasploitable2. |
| **Netcat** | Network Debugging | Successfully established a raw TCP connection (chat session) from Metasploitable2 to the Kali listener. |
| **Burp Suite** | Web Proxy | Successfully intercepted and forwarded the HTTP request to the Metasploitable2 web server. |
