# Hi, I'm Angel Ruiz 👋

CompTIA Security+ certified SOC Analyst with 250+ hours of hands-on cybersecurity training, a completed 30-day cloud SOC lab, and a drive to keep building.

📍 Northridge, CA · 🔐 SOC Analyst (Tier 1) | Cybersecurity Analyst
💼 [LinkedIn](https://www.linkedin.com/in/aruizcanel/) · ✉️ aruizcanel@yahoo.com

---

## 🔐 About Me

I came into cybersecurity after 10+ years in fast-paced, high-accountability operations roles — environments that demanded real-time monitoring, rapid problem-solving, and clear communication under pressure. Those fundamentals show up directly in how I approach SOC work.

I learn by doing. My labs are where theory turns into muscle memory — building real environments, running real attacks, then switching hats to detect and investigate everything I just did.

---

## 🎓 Certifications

### CompTIA Security+
[![CompTIA Security+](https://images.credly.com/images/80d8a06a-c384-42bf-ad36-db81bce5adce/linkedin_thumb_blob)](https://www.credly.com/badges/2755cc52-abf9-413f-874c-bef9ff8df79c)

> Certified June 2026 — Click badge to verify

---

### Correlation One — Information Security Analyst Program
**🏅 Graduated with Honors — July 6th, 2026**

> Completed 250+ hours of cybersecurity coursework including all labs, assessments, and professional development requirements. Achieved an average of 80%+ across all deliverables — awarded the Honors distinction. Sponsored by Amazon Career Choice.

**Program covered:**
`Wireshark` `Nmap` `Hydra` `Splunk` `MITRE ATT&CK` `IAM` `System Hardening` `Network Security` `Threat Detection` `Incident Response`

---

## 🛠️ Tools & Technologies

**SIEM & Detection**
`Elastic Stack (ELK)` `Kibana` `Splunk` `Sysmon` `Fleet Server` `Elastic Agent`

**Network Analysis**
`Wireshark` `Nmap` `tcpdump` `Netflow`

**Offensive Security**
`Metasploit` `msfvenom` `Hydra` `Crowbar` `Mythic C2` `Apollo Agent`

**Ticketing & Response**
`osTicket` `Alert-to-ticket workflows` `Incident documentation`

**Cloud & Virtualization**
`VULTR VPC` `Docker` `VirtualBox` `VM networking`

**Frameworks & Standards**
`MITRE ATT&CK` `NIST IR Lifecycle` `Kill Chain`

**Systems & Scripting**
`Linux CLI` `Windows CLI` `Bash` `PowerShell`

**Security Practices**
`System Hardening` `IAM` `Least Privilege` `Network Segmentation` `Defense Evasion Detection`

---

## 🏗️ Labs & Projects

### 1. MyDFIR 30-Day SOC Analyst Challenge *(Cloud — VULTR)*
> Full cloud-hosted SOC environment built from scratch over 30 days

**What I built:**
- ELK Stack (Elasticsearch + Kibana) for centralized SIEM
- Fleet Server managing Elastic Agents across Windows Server and Ubuntu Server
- Mythic C2 server deployed via Docker on an isolated external network
- osTicket integrated with Elastic via webhook for automatic alert-to-ticket workflow
- Custom Kibana detection rules and dashboards for SSH/RDP brute force, defense evasion, and C2 activity

**What I did:**
- Executed a full adversary simulation: RDP brute force → defense evasion → Mythic agent deployment → remote command execution → data exfiltration
- Investigated every phase from the defender's seat in Kibana — traced process chains, identified C2 callbacks, and documented complete investigation timelines in osTicket
- Detected real-world SSH/RDP brute force from internet-facing bots within minutes of port exposure
- Investigated an unrecognized international login captured in live RDP telemetry

📁 [View full writeup →](./mydfir-30-day-soc-challenge)

---

### 2. Home Lab — Attack & Detect Simulation *(Local VMs)*
> Isolated two-VM lab using Kali Linux and Windows 10

**What I built:**
- Internal virtual network with static IPs (Kali attacker + Windows 10 target)
- Splunk + Sysmon for centralized log detection

**What I did:**
1. Scanned target with Nmap → found RDP open on port 3389
2. Built a payload with msfvenom (Meterpreter reverse TCP)
3. Hosted payload via Python HTTP server
4. Established Metasploit listener → gained remote shell access
5. Detected the intrusion in Splunk — traced malicious process (god.pdf.exe spawning cmd.exe) and reconstructed full attack timeline via process GUID correlation

📁 [View full writeup →](./home-lab-attack-detect)

---

## ✅ Completed

- [x] CompTIA Security+ — Certified June 2026
- [x] Correlation One Information Security Analyst — Graduated with Honors July 2026
- [x] MyDFIR 30-Day SOC Analyst Challenge — Completed
- [x] Home lab — attack & detect simulation documented
- [x] TryHackMe — SOC Level 1 path (in progress)
- [x] CTF-style labs

## 🔄 Currently Working On

- [ ] Deeper Elastic detection rule engineering
- [ ] Python for log parsing and automation
- [ ] Windows Event ID deep dive
- [ ] Next lab build

---

## 📫 Let's Connect

I'm actively seeking **SOC Analyst** and **Cybersecurity Analyst** opportunities — entry-level, Tier 1, or junior roles.

- 💼 [LinkedIn](https://www.linkedin.com/in/aruizcanel/)
- 🖥️ [GitHub](https://github.com/ARUIZCANEL)
- 📧 aruizcanel@yahoo.com
- 📱 818-336-0898

---

*"Attacked it. Detected it. Documented it. That's the job."* 🔐
