# BreachLabs Writeups

A collection of my personal writeups for challenges from [BeachLabs](https://breachlab.org/tracks/).

## 📋 About BreachLab
BreachLab is an intuitive platform for learning linux exploitation through multiple challenges related to different areas of information technology and cybersecurity through hands-on challenges in various categories like system exploitation, information gathering, pentesting, software security, AI exploitation, DFIR, counter forensics, blue teaming, red teaming, mobile security, binary exploitation and RE, and more. It's basically an evolved version of OverTheWire.

## Rules of Engagement for the platform, as stated on the [BreachLab](https://breachlab.org/rules) website:
A free training ground for real offensive and defensive tradecraft. The labs stay open because operators behave like operators.

## Standing Orders
### 1 - Respect other operators.
Harassment, discrimination, or bad-faith conduct gets you removed. No grey area — the community is the asset.

### 2 - No spoilers.
Stuck? Use the per-track help threads on Discord — read the pinned #helprules first. Never drop passwords, flags, or hints in chat; the rooms are mirrored and spoiler tags don't survive.

### 3 - Leave the box clean.
No junk in /tmp, no half-finished payloads in shared dirs. The labs are shared infrastructure, not your scratch space — clean up when you close out.

### 4 - No brute force.
Automated guessing on passwords, flag submission, or SSH ingress is out of bounds. Read the system, don't flood it — we rate-limit and you'll get caught.

### 5 - Don't attack the platform.
The wargames are the target. The web app, host, database, and other operators' accounts are out of scope. Found a real vuln there? DM @ato for a Hall-of-Fame slot.

## Writeups · Creators
### 1 - Teach technique, never publish answers.
Writeups and videos are welcome when they teach the method — not the literal password or flag. Share technique-focused content in writeups.

### 2 - If it earns, give back.
BreachLab runs on donations. If content built on our tracks made you revenue, the donate page is right there.

### 3 - Credit BreachLab.
A link back or a name-drop in the description. That's it.

Using BreachLab means you've read these and you're in. No checkbox.

## 📚 Categories
| Path | Link | Status | Challenges Completed | Description |
|----------|--------|--------|---------------------|--------------|
| [Ghost](1%20-%20Ghost/) | [Ghost Path Link](https://breachlab.org/tracks/ghost) | 🟢 Started | 6 | Linux and shell fundamentals. Navigation, permissions, processes, encoding, network, SSH keys, port scanning, cron, git forensics, /proc. Where every operator starts. |
| [Phantom](2%20-%20Phantom/) | [Phantom Path Link](https://breachlab.org/tracks/phantom) | 🟡 Planning | 0 | Post-exploitation — the full chain. SUID, sudo, capabilities, kernel CVEs, credential harvesting, persistence, defense evasion, lateral movement, container escape, Kubernetes takeover, cloud pivot. |
| [Specter](3%20-%20Specter/) | [Specter Path Link](https://breachlab.org/tracks/specter) | 🟡 Planning | 0 | Recon & initial access — how you get in. A four-part series: OSINT, network & wireless, defence evasion & disruption, and social engineering. Specter I (OSINT, 14 levels) and Specter II (network & wireless, eight levels) are live; III–IV are planned. |
| [Mirage](4%20-%20Mirage/) | [Mirage Path Link](https://breachlab.org/tracks/mirage) | 🟡 Planning | 0 | Web application exploitation, in two parts. Mirage I — the full ladder from recon to AI, 41 browser targets: client trust, broken access control, BaaS/RLS, auth & tokens, the injection family, XSS, SSRF, deserialization, GraphQL, and AI/LLM attacks. Mirage II — the advanced sequel, 12 targets: cache deception, request smuggling, parser desync, HTTP/2 downgrade, single-packet races, and deserialization RCE. |
| [Cipher](5%20-%20Cipher/) | [Cipher Path Link](https://breachlab.org/tracks/cipher) | ⚫ Unavailable | 0 | Cryptography and password attacks. Hash cracking, TLS exploitation, padding oracle, RSA vulnerabilities, JWT forgery, credential stuffing. |
| [Nexus](6%20-%20Nexus/) | [Nexus Path Link](https://breachlab.org/tracks/nexus) | ⚫ Unavailable | 0 | CI/CD and supply chain. Git secrets, pipeline poisoning, dependency confusion, container registry attacks, IaC exploitation. |
| [Oracle](7%20-%20Oracle/) | [Oracle Path Link](https://breachlab.org/tracks/oracle) | ⚫ Unavailable | 0 | AI/LLM security. Prompt injection, jailbreaking, data exfiltration through LLMs, agent exploitation, RAG poisoning, model attacks. |
| [Wraith](8%20-%20Wraith/) | [Wraith Path Link](https://breachlab.org/tracks/wraith) | ⚫ Unavailable | 0 | Windows and Active Directory. PowerShell, token impersonation, Kerberoasting, pass-the-hash, DCSync, Golden Ticket, AMSI bypass, GPO abuse. |
| [Shadow](9%20-%20Shadow/) | [Shadow Path Link](https://breachlab.org/tracks/shadow) | ⚫ Unavailable | 0 | Anonymity, OPSEC, and darknet. Tor, VPN chains, anonymous communications, cryptocurrency privacy, counter-forensics, attribution resistance. |
| [Sentinel](10%20-%20Sentinel/) | [Sentinel Path Link](https://breachlab.org/tracks/sentinel) | ⚫ Unavailable | 0 | Blue team — the full SOC-to-DFIR arc. Log analysis & SIEM hunting, alert triage, incident response, endpoint & Windows forensics, memory & disk DFIR, malware analysis, network detection, threat hunting, CTI & attribution, detection engineering (Sigma/YARA/Suricata), cloud & identity detection, and detection-driven hardening. A purple-team through-line has you detect the exact TTPs you attacked in Ghost, Phantom, Mirage and Specter. |
| [Prism](11%20-%20Prism/) | [Prism Path Link](https://breachlab.org/tracks/prism) | ⚫ Unavailable | 0 | Apple security. macOS SIP/TCC/Gatekeeper bypass, Keychain extraction, iOS jailbreak fundamentals, app analysis, AirDrop exploitation. |
| [Venom](12%20-%20Venom/) | [Venom Path Link](https://breachlab.org/tracks/venom) | ⚫ Unavailable | 0 | Red team operations. C2 frameworks, implant development, payload delivery, infrastructure setup, EDR bypass, campaign planning, purple teaming. |
| [Flux](13%20-%20Flux/) | [Flux Path Link](https://breachlab.org/tracks/flux) | ⚫ Unavailable | 0 | Binary exploitation and reverse engineering. Stack overflow, ROP, heap, shellcoding, mitigation bypass, malware RE, firmware analysis, exploit development. |

## 📖 How to Use
1. Browse by path
2. Find the challenge you're working on
3. Read the writeup **after** attempting the challenge yourself. **Every writeups has been truncated to remove any flags, it only outlines the steps, as well as additional informations/general knowledge that are useful, you WILL need to do each step to get this type of information, this is to ensure that even if someone uses the writeups, they're still learning a lot**.
4. Learn and understand the techniques

## 📄 License
Licence CC BY-NC-SA 4.0 - [Creative Commons License](https://creativecommons.org/licenses/by-nc-sa/4.0/)