# 🌐 Networking for Cyber Security — Complete Professional Guide

![Cyber Security](https://img.shields.io/badge/Domain-Cyber%20Security-blue)
![Core Skill](https://img.shields.io/badge/Core-Networking-green)
![Level](https://img.shields.io/badge/Level-Student%20to%20Professional-orange)
![Focus](https://img.shields.io/badge/Focus-Network%20Defense-red)
![Hands On](https://img.shields.io/badge/Practice-Labs-purple)

---

# 📌 Overview

Networking is the **foundation of Cyber Security**. Every cyber attack, defense mechanism, monitoring system, and secure communication process operates through computer networks. To detect threats, prevent intrusions, and investigate incidents, strong networking knowledge is mandatory.

This guide provides complete, GitHub-ready notes on how networking is used in cyber security, including concepts, tools, attacks, defenses, labs, and a learning roadmap.

---

# 🎯 Why Networking is Critical in Cyber Security

- All cyber attacks travel through networks
- Threat detection depends on traffic analysis
- Security controls are placed at network layers
- Logs and packets provide forensic evidence
- Secure communication requires network encryption
- Attackers exploit network misconfigurations
- SOC and Threat Intelligence teams rely on network data

Without networking → cyber defense is incomplete.

---

# 🧠 Networking Fundamentals Required

## OSI Model (7 Layers)

1. Physical — cables, signals
2. Data Link — MAC, switching
3. Network — IP, routing
4. Transport — TCP/UDP
5. Session — connections
6. Presentation — encryption/format
7. Application — HTTP, FTP, DNS

Security relevance:
- Attacks target different layers
- Controls are applied per layer
- Packet analysis maps to layers

---

## TCP/IP Model

- Network Interface
- Internet
- Transport
- Application

Used in:
- Packet analysis
- Firewall rules
- IDS signatures
- Traffic filtering

---

# 🌍 Important Protocols in Cyber Security

| Protocol | Security Use |
|-----------|----------------|
HTTP | Insecure web traffic (monitor risk) |
HTTPS | Encrypted web traffic |
TLS/SSL | Encryption layer |
SSH | Secure remote access |
FTP | Insecure file transfer |
SFTP | Secure file transfer |
DNS | Domain resolution (attack target) |
DHCP | IP assignment |
IPSec | Secure IP tunnels |
SMTP | Email transport |

---

# 🏗️ Network Devices Used in Security

## Firewalls
- Filter traffic
- Allow/deny rules
- Port blocking
- Geo blocking
- Application filtering

## Routers
- Control packet routing
- Apply ACL rules
- Segment networks

## Switches
- VLAN segmentation
- MAC filtering
- Port security

## IDS (Intrusion Detection)
- Detect suspicious traffic
- Alert security teams

## IPS (Intrusion Prevention)
- Block malicious traffic automatically

## Proxy Servers
- Hide internal IP
- Filter requests
- Log user activity

---

# 🔐 Network Security Mechanisms

## Network Segmentation
- Divide network into zones
- Prevent lateral movement
- Limit breach spread

Examples:
- Internal network
- DMZ
- Guest network
- Admin network

---

## Zero Trust Model
- Trust nothing by default
- Verify every request
- Continuous authentication
- Least privilege access

---

## Defense in Depth
Multiple security layers:
- Firewall
- IDS/IPS
- Endpoint security
- Network monitoring
- SIEM

---

# 👁️ Network Monitoring & Detection

## Packet Inspection
- Analyze packet headers
- Detect anomalies
- Identify malware traffic

## Log Monitoring
- Firewall logs
- Router logs
- DNS logs
- Proxy logs

## Behavior Analysis
- Traffic spikes
- Unusual destinations
- Beaconing patterns

---

# 🚨 Common Network Attacks

## DDoS
- Traffic flooding
- Service disruption

## Man-in-the-Middle
- Traffic interception
- Credential theft

## ARP Spoofing
- Fake ARP replies
- Traffic redirection

## DNS Poisoning
- Fake DNS responses
- Redirect to malicious sites

## Packet Sniffing
- Capture credentials
- Monitor sessions

## Port Scanning
- Discover open services
- Reconnaissance phase

## Brute Force Attacks
- Network login guessing

---

# 🧰 Networking Tools for Cyber Security

| Tool | Purpose |
|------|----------|
Wireshark | Packet capture |
Nmap | Network scanning |
tcpdump | CLI packet capture |
Netcat | Network testing |
Snort | IDS |
Suricata | Network monitoring |
Burp Suite | Web traffic testing |
Zeek | Network analysis |
OpenVAS | Vulnerability scanning |

---

# 🧪 Practical Lab Exercises

## Lab 1 — Packet Capture
- Install packet analyzer
- Capture traffic
- Filter HTTP/DNS
- Identify IPs
- Export capture

## Lab 2 — Network Scanning
- Scan local subnet
- Identify open ports
- Detect services
- Run version scan

## Lab 3 — Port Risk Analysis
- Map ports → services
- Research risk level
- Suggest mitigation

## Lab 4 — Firewall Testing
- Block a port
- Test connectivity
- Compare results

## Lab 5 — DNS Analysis
- Capture DNS queries
- Identify suspicious domains

## Lab 6 — Traffic Pattern Study
- Monitor traffic for 10 minutes
- Note unusual behavior

## Lab 7 — Log Investigation
- Review firewall logs
- Identify failed logins
- Write incident summary

---

# 📊 Network Security Skills Checklist

## Beginner

- [ ] OSI model
- [ ] TCP/IP
- [ ] Ports & protocols
- [ ] Subnetting
- [ ] Packet basics
- [ ] DNS & DHCP

## Intermediate

- [ ] Packet capture
- [ ] Network scanning
- [ ] Firewall rules
- [ ] VPN concepts
- [ ] IDS/IPS basics
- [ ] Log reading

## Advanced

- [ ] Network forensics
- [ ] Malware traffic analysis
- [ ] Threat hunting
- [ ] Detection rules
- [ ] SIEM correlation
- [ ] Zero Trust design

---

# 🗺️ Cyber Security Networking Roadmap

## Phase 1 — Foundations
- Networking basics
- Protocols
- IP addressing
- Subnetting

## Phase 2 — Security Controls
- Firewalls
- IDS/IPS
- VPN
- Segmentation

## Phase 3 — Monitoring
- Packet analysis
- Log analysis
- Traffic profiling

## Phase 4 — Threat Detection
- Attack patterns
- Indicators of compromise
- Network anomalies

## Phase 5 — Professional Level
- SOC operations
- Threat intelligence
- Detection engineering
- Network forensics

---

# 💼 Career Roles That Require Networking

- SOC Analyst
- Cyber Security Analyst
- Threat Intelligence Analyst
- Network Security Engineer
- Incident Responder
- Penetration Tester
- Blue Team Analyst

---

# ✅ Final Conclusion

Networking is the **backbone of Cyber Security**. It enables:

- Threat detection  
- Attack prevention  
- Incident investigation  
- Secure communication  
- Defense architecture  

Master networking to become effective in cyber defense, SOC operations, and threat intelligence.

---

# ⭐ Usage

You can use this README as:

- Study reference
- GitHub portfolio project
- Cyber security roadmap
- Lab tracking guide
- Interview revision notes

---
