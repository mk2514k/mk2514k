# Mk

Security projects built through hands-on labs and independent research. Each
repo includes the reasoning behind the build, not just the output. Working
toward an entry-level blue team role.

---

### Certifications

`CompTIA Network+` `CompTIA Security+ (in-progress)` `eJPT (in-progress)`

---

### Focus Areas

**Detection Engineering** · **Network Security** · **Penetration Testing** ·
**Digital Forensics & IR** · **Threat Intelligence** · **Python Security Tooling**

---

### Tools & Stack

`Python` `Scapy` `Nmap` `Metasploit` `Burp Suite` `Wireshark` `Elastic SIEM`
`Splunk` `Sysmon` `Kali Linux` `OpenSSL` `OWASP ZAP` `Nginx` `Flask`
`Volatility 3` `pfSense` `Chart.js`

---

### Platforms

`TryHackMe` `HackTheBox` `OverTheWire` `VulnHub`

---

### Shipped Projects

| Repo | What it does |
|---|---|
|[Port-Scanner](https://github.com/mk2514k/Port-Scanner) | TCP port scanner with service banner grabbing, plus DNS enumeration with AXFR zone transfer attempts — built from raw sockets |
|[Password-Strength-Checker](https://github.com/mk2514k/Password-Strength-Checker) | Password validator built across three iterations, terminal script to a live-feedback GUI with strength bar and real-time checking |
|[Network_Security_Labs](https://github.com/mk2514k/Network-Security-Labs) | CompTIA Network+ hands-on practicals — packet analysis, network simulation, subnetting, IPv6 — documented with notes and screenshots |
| [Network-Packet-Analyser](https://github.com/mk2514k/Network-Packet-Analyser)) | Manually crafts ICMP, TCP SYN, and UDP packets with Scapy, verified against live Wireshark captures |
| [DNS-Recon-Advanced-Tool](https://github.com/mk2514k/DNS-Recon-Advanced-Tool) | DNS enumeration via AXFR zone transfer and threaded subdomain brute-forcing, tested against a deliberately misconfigured domain |
| overthewire-bandit | Full write-up series documenting methodology and key learnings for every Bandit level |
| [PKI-TLS-Auditor](https://github.com/mk2514k/PKI_TLS_Auditor) | Private CA chain built in OpenSSL (root → intermediate → leaf), Nginx hardened to TLS 1.2/1.3 only, Python audit script scoring cert chains, cipher strength, and expiry with clear remediation notes |

---

### Building Now — In Priority Order

| # | Project | Focus |
|---|---|---|
| 1 | Vulnerability Scanner + CVE Cross-Reference | Nmap scans cross-referenced against a local NVD CVE snapshot, CVSS-based severity scoring, HTML report output |
| 2 | IR Playbook Generator | CLI tool generating structured incident response playbooks (phishing, ransomware, breach, DDoS, insider threat) mapped to NIST SP 800-61 phases |
| 3 | Email Phishing Header Analyser | SPF/DKIM/DMARC validation, header chain analysis for spoofing, VirusTotal lookups, verdict output with evidence chain |
| 4 | AttackDetect — Purple Team Lab | Elastic SIEM / Splunk ingesting logs from Sysmon, Kali, and pfSense. Four simulated attacks, each documented with SIEM alert, raw log, MITRE ATT&CK mapping, and mini IR playbook. Includes a threat-hunting section run from a hypothesis. |
| 5 | Volatility Forensics Lab | Memory image analysis with Volatility 3 — process identification, injected process detection, network connection extraction, written up as an analyst report |
| 6 | Canary Token Generator & Alert System | Deception-based defense: fake credentials and config files that phone home when touched, Flask dashboard tracking triggers in real time |
| 7 | Threat Intel Dashboard | Flask backend pulling live from AlienVault OTX, CISA KEV, and NVD, rendered with Chart.js, auto-refreshing |

---

### Lab Environment

**Daily driver:** Fedora Linux (Niri compositor)
**VMs:** Kali Linux · Metasploitable 2 · Windows Server (AD labs) · pfSense (firewall/segmentation)
**Tools:** Wireshark · Nmap · Cisco Packet Tracer · Burp Suite · virt-manager · ipcalc · Volatility 3

---

🔗 LinkedIn · CV available on request
