# 🔵 Free SOC Analyst & Blue Team Resources, Labs & Roadmap

A curated, **verified-free** list of platforms, labs, datasets, and a step-by-step checklist to help you break into a **SOC Analyst / Blue Team** role — no paid subscriptions required.

> ✅ Every link below was checked as of **July 2026**. Free-tier limits (where they exist) are stated explicitly so you're never surprised by a paywall mid-lab.

---

## 📑 Table of Contents

- [Linux & Networking Fundamentals](#-linux--networking-fundamentals-free)
- [Hands-On Labs (Detailed)](#-hands-on-labs-detailed)
- [Free TryHackMe SOC Room Checklist](#-free-tryhackme-soc-room-checklist-beginner--advanced)
- [Learning Platforms](#-learning-platforms-free-tiers)
- [Practice Data & Logs](#️-practice-data--logs)
- [Blogs & Write-ups](#-blogs--write-ups)
- [Suggested Learning Path](#️-suggested-learning-path)
- [Why I Made This](#-why-i-made-this)
- [Contributing](#-contributing)

---

## 🐧 Linux & Networking Fundamentals (Free)

SOC/blue team work assumes solid Linux command-line and networking fundamentals — build that base before or alongside the SIEM-focused rooms below.

### Linux
- OverTheWire: Bandit — https://overthewire.org/wargames/bandit/ — free wargame, 30+ progressive levels teaching CLI basics (SSH, permissions, grep/find, cron, basic scripting); no signup, just SSH in with provided creds per level
- Linux Journey — https://linuxjourney.com/ — free interactive text-based course, grasshopper-to-sysadmin track
- ExplainShell — https://explainshell.com/ — paste any command and get a breakdown of every flag

### Networking
- Professor Messer: Network+ (N10-009) Full Course — https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-comptia-network-plus-course/ — complete free video course covering OSI model, IP addressing/subnetting, routing/switching, wireless, and troubleshooting
- Practical Networking — https://www.practicalnetworking.net/ — free articles and video series on TCP/IP, subnetting, and routing
- Cisco NetAcad: Networking Basics — https://www.netacad.com/courses/networking-basics — free, self-paced intro course covering fundamentals, IP addressing, and troubleshooting
- Subnetting Practice — https://subnettingpractice.com/ — free drills; subnetting math comes up often in interviews

---

## 🧪 Hands-On Labs (Detailed)

### LetsDefend (https://letsdefend.io/)
- Free Basic account gives free courses, challenges, and quizzes, plus 15 real SOC alert investigations per month in an actual SIEM-style dashboard
- You triage real alerts: check logs, pivot on IOCs, decide escalate/close
- VIP/VIP+ unlock unlimited alerts, more courses, and a career-path certification — but the free 15/month is genuinely enough to build real triage habits
- Bonus: LetsDefend also maintains a free, open Cybersecurity Resources list on GitHub worth bookmarking

### TryHackMe (https://tryhackme.com/)
- Free rooms worth doing: SOC Level 1 path (partially free), Intro to SIEM, Wireshark, Investigating Windows
- Browser-based VMs, no local setup needed
- See the ordered, free-room checklist below

### CyberDefenders (https://cyberdefenders.org/blue-team-labs/)
- Free blue team CTF-style challenges using real pcaps, memory dumps, and logs
- Categories: network forensics, endpoint forensics, malware analysis, threat intel
- Each challenge has a write-up community so you can compare your approach after solving
- Fully free to attempt challenges; no paywall on core content

### Blue Team Labs Online / BTLO (https://blueteamlabs.online/)
- Free tier gives numerous free challenges plus a couple of free "Investigations" (real scenario-based labs) each month
- Gamified with points, ranks, and leaderboards
- Unlimited investigations require PRO — but free challenges alone cover phishing analysis, digital forensics, and SOC scenarios
- Free intro path: Blue Team Junior Analyst Pathway — 6 free courses + certificate of completion

### Security Onion (https://github.com/Security-Onion-Solutions/securityonion)
- 100% free, open-source network security monitoring + SIEM distro (Suricata, Zeek, Elastic stack bundled in)
- Best used in a home lab: spin up in VirtualBox/VMware, feed it PCAPs or live traffic from a test network
- Great for a portfolio project — document your setup, detections, and findings

### Wazuh (https://documentation.wazuh.com/current/quickstart.html)
- Free, open-source SIEM + XDR platform
- Install on a VM, connect endpoint agents (Windows/Linux), and practice writing detection rules
- Good for demonstrating log correlation and alerting skills in your GitHub portfolio

### Bonus: Free Lab-Building Projects
- DetectionLab (https://github.com/clong/DetectionLab) — scripts to auto-build a Windows AD lab with Splunk + Sysmon pre-configured for detection practice
- Splunk BOTS v3 (https://github.com/splunk/botsv3) (also v1, v2) — free downloadable datasets simulating real breaches, with guided questions so you can practice hunting in Splunk's free tier

---

## ✅ Free TryHackMe SOC Room Checklist (Beginner → Advanced)

### 1️⃣ Foundations
- [ ] SOC Role in Blue Team — https://tryhackme.com/room/socroleinblueteam
- [ ] Defensive Security Intro — https://tryhackme.com/room/defensivesecurityintroqW
- [ ] Intro to Logs — https://tryhackme.com/room/introtologs
- [ ] Introduction to SIEM — https://tryhackme.com/room/introtosiem

### 2️⃣ SIEM Tooling
- [ ] Splunk: Exploring SPL — https://tryhackme.com/room/splunkexploringspl

### 3️⃣ Windows & Linux Log Analysis
- [ ] Windows Logging for SOC — https://tryhackme.com/room/windowsloggingforsoc
- [ ] Investigating Windows — https://tryhackme.com/room/investigatingwindows
- [ ] Investigating Windows 2.0 — https://tryhackme.com/room/investigatingwindows2
- [ ] Windows Threat Detection 1 — https://tryhackme.com/room/windowsthreatdetection1
- [ ] Linux Logging for SOC — https://tryhackme.com/room/linuxloggingforsoc
- [ ] Linux Threat Detection 1 — https://tryhackme.com/room/linuxthreatdetection1
- [ ] Linux Server Forensics — https://tryhackme.com/room/linuxserverforensics

### 4️⃣ Network Traffic Analysis
- [ ] Network Traffic Analysis Basics — https://tryhackme.com/room/networktrafficbasics
- [ ] TShark — https://tryhackme.com/room/tshark
- [ ] Network Security Essentials — https://tryhackme.com/room/networksecurityessentials
- [ ] Network Discovery Detection — https://tryhackme.com/room/networkdiscoverydetection
- [ ] h4cked — https://tryhackme.com/room/h4cked
- [ ] Event Horizon — https://tryhackme.com/room/eventhorizonroom

### 5️⃣ Endpoint & Memory Forensics
- [ ] Introduction to EDR — https://tryhackme.com/room/introductiontoedrs

### 6️⃣ Malware Analysis & Threat Hunting
- [ ] YARA: Threat Hunting with YARA — https://tryhackme.com/room/threathuntingwithyara
- [ ] File and Hash Threat Intel — https://tryhackme.com/room/fileandhashthreatintel
- [ ] APT Detection: Volt Typhoon — https://tryhackme.com/room/volttyphoon

### 7️⃣ Incident Response & Alert Triage
- [ ] IR Playbooks — https://tryhackme.com/room/irplaybooks
- [ ] SOC L1 Alert Reporting — https://tryhackme.com/room/socl1alertreporting
- [ ] SOC L1 Alert Triage — https://tryhackme.com/room/socl1alerttriage
- [ ] Identification & Scoping — https://tryhackme.com/room/identificationandscoping
- [ ] AppSec IR — https://tryhackme.com/room/appsecir
- [ ] Detecting Web Attacks — https://tryhackme.com/room/detectingwebattacks
- [ ] Chaining Vulnerabilities — https://tryhackme.com/room/chainingvulnerabilitiesZp

### 8️⃣ Capstone Challenges
- [ ] CCT2019 — https://tryhackme.com/room/cct2019

---

## 📚 Learning Platforms (Free Tiers)

- Cybrary — free courses covering SOC fundamentals, incident response, and vulnerability management — https://www.cybrary.it/
- Cisco NetAcad – Introduction to Cybersecurity — free intro course — https://www.netacad.com/courses/cybersecurity/introduction-cybersecurity
- Cisco NetAcad – CyberOps Associate prep — free material aligned with the CyberOps Associate cert — https://www.netacad.com/courses/cyberops-associate
- Professor Messer – Security+ (SY0-701) Full Course — complete free video course — https://www.professormesser.com/security-plus/sy0-701/sy0-701-video/sy0-701-comptia-security-plus-course/
- Professor Messer – Network+ (N10-009) Full Course — complete free video course — https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-comptia-network-plus-course/
- MITRE ATT&CK — the framework every SOC detection should map to — https://attack.mitre.org/
- ATT&CK Navigator — visualize and track technique coverage — https://mitre-attack.github.io/attack-navigator/

---

## 🗂️ Practice Data & Logs

- Malware-Traffic-Analysis.net — real pcaps with write-ups — https://www.malware-traffic-analysis.net/
- JPCERT EVTX-ATTACK-SAMPLES — sample Windows Event Logs mapped to attack techniques — https://github.com/JPCERTCC/EVTX-ATTACK-SAMPLES
- Splunk BOTS v3 Dataset — https://github.com/splunk/botsv3
- DetectionLab — auto-provisioned AD + Splunk + Sysmon lab environment — https://github.com/clong/DetectionLab

---

## 📝 Blogs & Write-ups

- LetsDefend Blog — real investigation write-ups — https://letsdefend.io/blog
- CyberDefenders Blog — challenge walkthroughs and analysis techniques — https://cyberdefenders.org/blog/

---

## 🗺️ Suggested Learning Path

1. **Linux & Networking Prep** → Bandit + Linux Journey + Professor Messer Network+ (skip if already comfortable with CLI/networking)
2. **Foundations** → Professor Messer Security+ + Cisco Intro to Cybersecurity
3. **SIEM Practice** → Work through the TryHackMe checklist above → LetsDefend simulations
4. **Investigation Skills** → CyberDefenders challenges → BTLO scenarios
5. **Build Your Own Lab** → Deploy Security Onion, Wazuh, or DetectionLab; simulate attacks, document findings
6. **Portfolio** → Write up every lab/challenge you complete

---

## 🙋 Why I Made This

Built while going through my own SOC analyst prep — every resource here is something actually used or vetted.

---

## 🤝 Contributing

Found a great free resource that's missing, or a link that's gone stale? Open a PR or an issue.
