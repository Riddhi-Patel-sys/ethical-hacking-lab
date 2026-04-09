# 🔐 Hands-On Ethical Hacking — Penetration Testing Lab Report

A network security assessment conducted in a **controlled virtual lab environment** using industry-standard tools and methodologies.

> ⚠️ **Disclaimer:** All testing was performed exclusively within an isolated VirtualBox host-only network. No external systems, public networks, or real-world machines were involved or affected.

## 📋 Project Overview

This project involved performing a **grey-box, network-level penetration test** on a set of virtual machines to identify exposed services, open ports, and potential vulnerabilities — without exploiting any systems.

## 🖥️ Lab Environment

| Machine | Role | IP Address |
|---|---|---|
| Kali Linux VM | Testing machine / attacker | 192.168.56.x |
| Metasploitable2 VM | Intentionally vulnerable target | 192.168.56.104 |
| Axigen-Ubuntu VM | Linux mail/web server | 192.168.56.x |
| Host Computer | Detected in host-only network | Scanned within isolated subnet only |

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Nmap** | Host discovery, port scanning, service/version detection |
| **Netcat (nc)** | Manual HTTP request sending, banner grabbing |
| **wget** | Downloading web content for analysis |
| **enum4linux** | SMB/Samba enumeration — users, shares, OS info |
| **Nessus Essentials** | Automated vulnerability scanning |
| **CVE / NVD Databases** | Researching identified vulnerabilities |

## 🔍 Testing Methodology

- **Grey-box testing** — Basic knowledge of lab setup was known in advance
- **Network-level** — Focus on exposed services and discoverable information
- **Non-exploitative** — No exploitation, brute-forcing, or system damage attempted

## 📚 Skills Demonstrated

- Network reconnaissance and host discovery
- Port scanning and service fingerprinting
- Vulnerability identification (manual + automated)
- CVE/NVD database research
- Technical security report writing
- Safe, ethical, and controlled testing practices

## 👩‍💻 Author

**Riddhi Patel**  
BTech Information Technology — Kwantlen Polytechnic University  
📧 riddhi.patel@student.kpu.ca
