<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:00ff88,100:00d4ff&height=200&section=header&text=RITHIKA%20U&fontSize=40&fontColor=000000&fontAlignY=35&desc=Cybersecurity%20Engineer%20%7C%20Ethical%20Hacker%20%7C%20RIVI%20Enterprises%20%7C%20Chennai&descAlignY=55&descColor=000000&animation=fadeIn)

</div>

---

```bash
$ whoami
  Rithika U | Cybersecurity Engineer & Ethical Hacker | Chennai, India
  Company : RIVI Enterprises
  Status  : Breaking things ethically. Building secure tools for everyone.

$ cat mission.txt
  Detect. Defend. Disrupt.
  Security is not just for experts — everyone deserves to feel safe online.

$ ls certifications/
  ISC2_CC  Fortinet_FCF  Fortinet_FCA  Cisco_EthicalHacker  Cisco_NetworkDefense
  IBM_CyberFundamentals  GoogleCloud_SecOps  IITMadras_EthicalHacking  INFYSEC_CEC
```

---

## 🖥️ Technical Skills

```ini
[OFFENSE]
tools     =  Nmap | Burp Suite | Metasploit | SQLMap | Hydra | Wireshark | Scapy | Impacket | Mimikatz
platforms =  TryHackMe | HackTheBox | PortSwigger | DVWA | VulnHub
certs     =  Cisco Ethical Hacker | Fortinet FCF/FCA | INFYSEC Certified Ethical Cracker

[DEFENSE]
siem      =  Wazuh | Splunk | Suricata IDS | Google SecOps
forensics =  Volatility3 | Autopsy | Sysmon | CAPEv2 Sandbox
intel     =  MISP | AbuseIPDB | VirusTotal API | Shodan | MITRE ATT&CK

[DEV]
languages =  Python | JavaScript | TypeScript | Bash | PowerShell
stack     =  Next.js | Flask | React | Tailwind CSS | Docker | SQLite
cloud     =  Azure | Google Cloud | AWS | Kali Linux | VirtualBox | VMware
```

---

## 🔴 Offensive Security Projects

| # | Project | Description | Stack | Impact |
|---|---------|-------------|-------|--------|
| 01 | [🏹 Auto-Pentest Framework](https://github.com/rithika-ujjalsingh/Auto-pentest-framework) | Python CLI — chains recon → scan → exploit → HTML/PDF report automatically | Python, Nmap, Metasploit, Bash | ★★★★★ |
| 02 | [🛡️ AD Attack & Defense Lab](https://github.com/rithika-ujjalsingh/AD-attack-defense-lab) | Build CORP.LOCAL domain, attack with Kerberoasting + Pass-the-Hash + DCSync, defend with Wazuh | Impacket, Windows Server, Mimikatz | ★★★★★ |
| 03 | [🕷️ Web Vulnerability Scanner](https://github.com/rithika-ujjalsingh/Web-vulnerability-scanner) | Automated SQLi, XSS, LFI, SSRF, security header scanner — targets DVWA & Juice Shop | Python, BS4, Requests | ★★★★★ |
| 04 | 🔴 Full Red Team C2 Infrastructure | Sliver C2 framework, BloodHound AD enumeration, lateral movement, full red team report | Sliver, BloodHound, Kali Linux | ★★★★★ |
| 05 | 📡 WiFi Security Audit Lab | WPA2 handshake capture, evil twin AP, deauth attacks, WPS vuln testing on own router | Aircrack-ng, Hostapd, Python | ★★★★☆ |
| 06 | 💉 Manual SQL Injection Lab | Error-based, UNION, Blind, Time-based SQLi — manual + SQLmap. Deep OWASP A03 coverage | SQLmap, Python, DVWA | ★★★★☆ |

---

## 🔵 Defensive Security Projects

| # | Project | Description | Stack | Impact |
|---|---------|-------------|-------|--------|
| 07 | [🏠 Home SOC Lab](https://github.com/rithika-ujjalsingh/ids-network-project) | Complete SOC: Wazuh SIEM + Suricata IDS, real attack simulation, alerting & response | Wazuh, Suricata, VirtualBox | ★★★★★ |
| 08 | [📡 Network IDS — Scapy](https://github.com/rithika-ujjalsingh/ids-network-project) | Custom IDS from scratch — SYN flood, port scan, ARP spoofing detection + Flask dashboard | Python, Scapy, Flask, SQLite | ★★★★★ |
| 09 | 🍯 Honeypot Network | Cowrie SSH honeypot + OpenCanary on real VPS. Collect real attacker data + Flask viz | Cowrie, OpenCanary, Flask | ★★★★☆ |
| 10 | 📊 Log Analysis & Threat Hunter | Parse Apache/Nginx/SSH logs. Detect brute-force, 404 floods, SQLi. Chart.js dashboard | Python, Flask, Chart.js | ★★★★☆ |
| 11 | 🔬 Digital Forensics Lab | Volatility3 memory analysis, Autopsy disk forensics, IOC extraction, timeline reconstruction | Volatility3, Autopsy, Python | ★★★★☆ |
| 12 | 🖥️ Endpoint Detection (EDR) — Sysmon | Custom EDR: Sysmon events + Python alerting. Detect process injection, LSASS access | Sysmon, Python, Windows | ★★★★☆ |

---

## 🟣 Malware Analysis & CTI Projects

| # | Project | Description | Stack | Impact |
|---|---------|-------------|-------|--------|
| 13 | 🦠 Malware Sandbox — CAPEv2 | Automated sandbox: detonate suspicious files in isolated VM → MITRE ATT&CK mapped report | CAPEv2, Python, VirtualBox | ★★★★★ |
| 14 | [🔍 YARA Malware Scanner](https://github.com/rithika-ujjalsingh) | Scan files with YARA rules — PE malware, ransomware strings, shellcode detection + VirusTotal | Python, YARA, VirusTotal API | ★★★★★ |
| 15 | 🧠 Threat Intelligence Platform (MISP) | MISP + Python IOC enrichment (VirusTotal + AbuseIPDB + Shodan). Public feed ingestion | MISP, Python, Shodan | ★★★★★ |
| 16 | [🔎 OSINT Recon Automation Tool](https://github.com/rithika-ujjalsingh) | DNS enum, WHOIS, Shodan, GeoIP, subdomain brute-force → JSON+HTML recon report | Python, Shodan, dnspython | ★★★★☆ |
| 17 | 🔒 Ransomware Behavior Detector | Real-time file system monitor — detect mass modifications, entropy spikes, extension changes | Python, watchdog, Windows API | ★★★★☆ |

---

## 🟡 Cloud & Network Security Projects

| # | Project | Description | Stack | Impact |
|---|---------|-------------|-------|--------|
| 18 | ☁️ AWS Cloud Security Scanner | Audit public S3 buckets, permissive IAM, open SGs, unencrypted EBS — CIS AWS mapped | Python, boto3, AWS CLI | ★★★★★ |
| 19 | 📦 Packet Analyzer & Custom IDS | Deep packet inspection, custom detection rules, protocol fingerprinting, PCAP export | Python, Scapy, dpkt | ★★★★☆ |
| 20 | 🌐 DNS Security Monitor | DNS tunneling detection, NXDOMAIN flood alerts, suspicious domain age checking, blocklist | Python, dnslib, Scapy | ★★★★☆ |
| 21 | 🔒 VPN & Proxy Detector | Detect Tor exit nodes, VPN IPs, proxy IPs via threat intel feeds and IP reputation APIs | Python, Requests, MaxMind | ★★★☆☆ |
| 22 | 🔐 SSL/TLS Audit Tool | Detect weak ciphers (RC4, DES), expired certs, HSTS missing, TLS 1.0/1.1 | Python, testssl.sh, cryptography | ★★★★☆ |

---

## 🟢 SOC Tools & AppSec Projects

| # | Project | Description | Stack | Impact |
|---|---------|-------------|-------|--------|
| 23 | 🚨 CVE Vulnerability Tracker | NVD API polling, CVSS filtering, asset-CVE mapping, email/Slack alerts | Python, NVD API, Flask | ★★★★☆ |
| 24 | 📧 Phishing Email Analyzer | Parse headers, check SPF/DKIM/DMARC, extract + VT-scan all URLs, generate report | Python, email, VirusTotal API | ★★★★★ |
| 25 | [🔑 Password Audit Tool](https://github.com/rithika-ujjalsingh/password-security-lab) | AD password policy checker, NTLM hash extraction, hashcat integration | Python, bcrypt, hashcat | ★★★★☆ |
| 26 | ⚡ SOAR Automation Scripts | Auto IP blocking on alert, Jira ticket creation, Slack notifications — Wazuh API | Python, Wazuh API, Jira API | ★★★★★ |
| 27 | 🌑 Dark Web Monitor | Tor SOCKS scraping, keyword alerting for brand/email/credentials, threat tracking | Python, Tor, BeautifulSoup | ★★★☆☆ |
| 28 | 🔌 API Security Tester | REST/GraphQL fuzzing, auth bypass, IDOR detection, rate limiting — OWASP API Top 10 | Python, Requests, Burp Suite | ★★★★★ |
| 29 | 📱 Mobile App Security Auditor | Android APK static analysis — MobSF, hardcoded secrets, manifest permissions audit | MobSF, ADB, Python | ★★★★☆ |
| 30 | 📈 SOC Analytics Dashboard | Real-time SOC KPIs — Wazuh API, MTTD/MTTR metrics, threat trending, React + Flask | React, Flask, Wazuh API | ★★★★★ |

---

## ✅ Flagship Live Projects

| # | Project | Description | Stack | Status |
|---|---------|-------------|-------|--------|
| 🛡️ | [PhishShield Pro](https://github.com/rithika-ujjalsingh/Shield-pro) | Chrome Manifest V3 extension — real-time XSS & phishing URL detection | JS, Chrome APIs | ✅ Live |
| 🤖 | [Maayon AI](https://github.com/rithika-ujjalsingh/Maayon-AI) | AI-powered pentesting assistant — payloads, CVE explanations, attack paths | Next.js, OpenAI API | ✅ Live |
| 🔒 | [File Integrity Monitor](https://github.com/rithika-ujjalsingh/file-integrity-checker) | SHA-256 forensic audit tool — detect unauthorised file modifications | Python, SQLite | ✅ Live |
| 🔎 | [Network Port Scanner](https://github.com/rithika-ujjalsingh/Network-port-scanner) | Multi-threaded recon utility with service fingerprinting | Python, Socket | ✅ Live |

---

## 🏆 Certifications

**Cybersecurity**

| Issuer | Certification |
|--------|--------------|
| ISC2 | Certified in Cybersecurity (CC) |
| Cisco NetAcad | Ethical Hacker |
| Cisco NetAcad | Network Defense |
| Cisco NetAcad | Endpoint Security |
| Cisco NetAcad | Network Support & Security |
| Fortinet | FCF — Network Security Fundamentals |
| Fortinet | FCA — Fortinet Certified Associate |
| Google Cloud | Security Operations Fundamentals |
| Google Cloud | Security Operations Deep Dive |
| IBM SkillsBuild | Cybersecurity Fundamentals |
| IBM SkillsBuild | Threat Intel · OSINT · Incident Response |
| INFYSEC | Certified Ethical Cracker |
| IIT Madras | Ethical Hacking — TECHOBYTES 2025 |
| LinkedIn Learning | Cybersecurity Foundations |

**Networking & Systems**

| Issuer | Certification |
|--------|--------------|
| Cisco NetAcad | CCNA: Routing & Switching |
| Cisco NetAcad | Computer Hardware Basics |
| Cisco NetAcad | Exploring Networking with Packet Tracer |
| Cisco NetAcad | Operating Systems Basics |
| Vector Techno Soft | Advanced Diploma — Computer Hardware & Networking |

**Industrial Training & Workshops**

| Issuer | Event |
|--------|-------|
| ISRO | Satish Dhawan Space Centre — Sriharikotta (2017) |
| BSNL | Industrial Visit (2018) |
| UNIQ Technologies | Android App Development Workshop (2017) |
| UNIQ Technologies | In-Plant Training (Nov 2017) |

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=rithika-ujjalsingh&show_icons=true&theme=matrix&hide_border=true&bg_color=0d1117&title_color=00ff88&text_color=00d4ff&icon_color=00ff88)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rithika-ujjalsingh&layout=compact&theme=matrix&hide_border=true&bg_color=0d1117&title_color=00ff88&text_color=00d4ff)

![GitHub Streak](https://streak-stats.demolab.com?user=rithika-ujjalsingh&theme=matrix&hide_border=true&background=0d1117&ring=00FF00&fire=00FF00&currStreakLabel=00FF00)

</div>

---

## 🧠 Learning & Progress

```
[COMPLETED]   Auto-Pentest Framework                   ████████████  100%
[COMPLETED]   AD Attack & Defense Lab                  ████████████  100%
[COMPLETED]   PhishShield Pro Chrome Extension         ████████████  100%
[COMPLETED]   PortSwigger SQLi, XSS, CSRF, Auth Labs   ████████████  100%
[COMPLETED]   HackTheBox Starting Point                ████████████  100%
[COMPLETED]   Active Directory Home Lab Setup          ████████████  100%
[COMPLETED]   DVWA All Security Levels                 ████████████  100%
[COMPLETED]   Network IDS (Scapy + Flask)              ████████████  100%
[COMPLETED]   File Integrity Monitor                   ████████████  100%
[COMPLETED]   Web Vulnerability Scanner                ████████████  100%
[IN PROGRESS] TryHackMe Jr. Penetration Tester         █████████░░░   75%
[IN PROGRESS] Home SOC Lab — Wazuh + Suricata          ████████░░░░   70%
[IN PROGRESS] OSINT Recon Automation Tool              ██████░░░░░░   55%
[IN PROGRESS] YARA Malware Scanner                     █████░░░░░░░   45%
[LEARNING]    Bug Bounty — HackerOne & Bugcrowd        ████░░░░░░░░   40%
[UPCOMING]    CEH — Certified Ethical Hacker           ░░░░░░░░░░░░  Starting
[UPCOMING]    OSCP — Offensive Security                ░░░░░░░░░░░░  Planned
```

---

## 🌍 Mission — Security for Everyone

> Security is not just for experts.
>
> I build tools that protect normal people from real threats — phishing attacks, weak passwords, file tampering, and network intrusions. Whether you are a student, a senior citizen, or a small business in Chennai, you deserve to feel secure online.
>
> **Free security advice for students and seniors** — reach out anytime.
>
> Founder · RIVI Enterprises

---

## 📡 Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-rithika--ujjalsingh.github.io-00ff88?style=for-the-badge&logoColor=black)](https://rithika-ujjalsingh.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rithikasingh2626)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rithika-ujjalsingh)
[![Credly](https://img.shields.io/badge/Credly-Badges-FF6B00?style=for-the-badge&logo=credly&logoColor=white)](https://credly.com/users/rithika-u.ad84195d)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Profile-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rithisingh2020@gmail.com)

</div>

---

<div align="center">

**[ SYSTEM STATUS: ONLINE ] [ THREAT LEVEL: HUNTING ] [ MODE: BUILDING → BREAKING → DEFENDING ]**

*"The quieter you become, the more you can hear."* — Kali Linux

![Visitor Count](https://komarev.com/ghpvc/?username=rithika-ujjalsingh&color=00ff88&style=flat-square&label=PROFILE+VIEWS)

</div>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,100:00ff88&height=100&section=footer)
