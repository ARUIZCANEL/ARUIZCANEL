# Hi, I'm Angel Ruiz 👋

Cybersecurity professional in training, building toward a SOC Analyst role through hands-on labs, real-world tools, and a CompTIA Security+ certification.

📍 Northridge, CA · 🔐 SOC Analyst (Tier 1) | Cybersecurity Analyst
🌐 [LinkedIn](https://www.linkedin.com/in/aruizcanel/) · ✉️ aruizcanel@yahoo.com

---

## 🔐 About Me

I'm transitioning into cybersecurity after 10+ years across operations-heavy roles — fast-paced environments that demanded real-time monitoring, strict protocol adherence, and rapid problem-solving. Those fundamentals now show up directly in how I approach SOC work: watching for anomalies, following process under pressure, and communicating clearly when something's wrong.

I learn by doing. My home lab is where theory turns into muscle memory — running real attacks, then switching hats to detect and trace them myself.

- 🎓 **CompTIA Security+** — Certified 
- 🎓 **Correlation One Cybersecurity Program** — Graduating with honors (July 2026)
- 🏠 Actively building and breaking things in a personal home lab
- 🇺🇸 🇲🇽 Bilingual — English & Spanish

---

## 🛠️ Tools & Technologies

**SIEM & Log Analysis**
`Splunk` `Sysmon` `Windows Event Viewer`

**Network Analysis**
`Wireshark` `Nmap` `tcpdump`

**Offensive Security**
`Hydra` `Metasploit` `msfvenom`

**Frameworks**
`MITRE ATT&CK`

**Systems & Scripting**
`Linux CLI` `Windows CLI` `Bash` `PowerShell basics`

**Security Practices**
`System Hardening` `IAM` `Least Privilege` `Network Segmentation`

---

## 🏠 Home Lab

A self-built, fully isolated virtual environment used to practice both offensive and defensive security — attacking on one side, detecting on the other.

**Current setup:**
- **Kali Linux** (attacker) + **Windows 10** (target) on an internal virtual network with static IPs
- **Splunk + Sysmon** for centralized logging and detection
- Practicing the full attack lifecycle: reconnaissance → exploitation → execution → detection → investigation

**Recent lab — Attack & Detect Simulation:**
1. Scanned target with `Nmap` → discovered RDP open (port 3389)
2. Built a payload with `msfvenom` (Meterpreter reverse TCP)
3. Delivered the payload via a local Python web server
4. Established a Metasploit listener and gained shell access
5. Pivoted to defense — used **Splunk** to trace the attacker's IP, identify the malicious process spawning `cmd.exe`, and reconstruct every command executed using the process GUID

This loop — break it, then catch yourself breaking it — is the core practice I keep coming back to.

---

## 📚 Currently Learning

- [ ] TryHackMe — SOC Level 1 path
- [ ] CTF-style labs
- [ ] Deeper Splunk SPL query writing
- [ ] Windows Event ID deep dive for detection engineering
- [ ] Python for log parsing and automation

---

## 📫 Let's Connect

I'm actively seeking entry-level **SOC Analyst** and **Cybersecurity Analyst** opportunities. Open to internships, mentorship, and conversations with anyone in the field.

- 💼 [LinkedIn](https://www.linkedin.com/in/aruizcanel/)
- 📧 aruizcanel@yahoo.com
- 📱 818-336-0898

---

*"Attacked it. Then caught it. That's the loop I'm here to learn."*--
