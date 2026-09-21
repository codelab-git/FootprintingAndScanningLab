<div align="center">

# 🔐 FOOTPRINTING & RECONNAISSANCE

**Carryout footprint and reconnaissance on networkwalks.com using six built-in Kali Linux tools:
whois, whatweb, nslookup, curl, wafw00f, dnsrecon and nmap for scanning**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />

</p>

---

## 📌 Project Overview

This lab project applied core reconnaissance techniques from the penetration testing lifecycle across two environments: an external domain and an internal network.

In the first phase, footprinting was performed against networkwalks.com using six Kali Linux tools: WHOIS, WhatWeb, Nslookup, Curl, Wafw00f, and DNSRecon. This revealed domain registration details, the site's technology stack (WordPress 7.1.1 with the WP Download Manager plugin), its hosting IP, HTTP header configuration, an active ModSecurity WAF, and its full DNS record set (mail servers, SPF policy, and name server software).

In the second phase, active scanning was carried out on a local LAN using Zenmap, the graphical front end for Nmap. This identified five live hosts on the subnet and produced a visual network topology map showing how devices connect to the scanning host.

Together, the two phases demonstrate the natural progression of reconnaissance: starting with passive, publicly available information gathering about an external target, then moving to active internal host discovery. The exercise reinforced how even routine, non-intrusive queries can expose meaningful technical detail, and why documenting findings with clear evidence and risk context is a core skill in cybersecurity assessment work.

---


## 🎯 Objectives

The main objectives of this project are to:

- Run whois to find the domain registration details.
- Run whatweb to fingerprint the web technologies.
- Run nslookup to resolve the domain to its IP address.
- Run curl -I to read the HTTP response headers.
- Run wafw00f to detect a Web Application Firewall.
- Run dnsrecon to enumerate all DNS records.

---

# 💡 What I Learned

Through this project, I learned how to carryout footprinting and reconnaissance.

The most important concepts I learned include:

### 1. OSINT and domain footprinting

Using WHOIS, WhatWeb, Nslookup, Curl, and DNSRecon to build a technical profile of a target domain from publicly available information alone.

### 2. Web technology and infrastructure fingerprinting

Identifying a site's CMS, plugins, server software, and hosting setup, and understanding why version disclosure matters to an attacker.

### 3. Network host discovery and mapping

Using Zenmap/Nmap to scan a subnet, identify live hosts, and generate a visual network topology.

### 4. Security risk analysis and reporting

Translating raw tool output into a structured risk table with findings, evidence, impact, and severity ratings, distinguishing observations from confirmed vulnerabilities.

### 5. Professional pentest documentation

 Writing a client-ready report with a liability disclaimer, scoped objectives, evidence screenshots, and actionable recommendations, following an industry-style reporting format.

---

# 🔐 Security & Ethical Use

This laboratory is intended strictly for education purposes only.

---

# 🔗 Tools & Resources

- **nmap:** [https://nmap.org/download.html](https://nmap.org/download.html)
- **Kali Linux:** [https://kali.org/get-kali](https://kali.org/get-kali)

---
