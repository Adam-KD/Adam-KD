# Adam Kadmany                           
**Cybersecurity Analyst - SOC Operations & Threat Detection**                        
Majdal Shams, Golan Heights, Israel

---

## About

Cybersecurity analyst focused on SOC operations, threat detection, and hands-on attack simulation. I build controlled lab environments, execute real attack scenarios end-to-end, document findings, and publish everything.

CompTIA Security+ certified. ICS College SOC graduate. TryHackMe Top 2% globally. Pursuing CCNA.

Multilingual: Arabic (native), English (C1), Hebrew (working proficiency), German (A1).

---

## Featured Projects

### [SOC Simulations Home Lab](https://github.com/Adam-KD/soc-simulations)
A segmented multi-VM SOC lab (Kali, Ubuntu gateway, two Windows endpoints) with Wazuh SIEM, Sysmon telemetry, and centralized traffic routing; simulating real SOC network architecture. Each simulation includes full Wireshark packet analysis, Wazuh alert correlation, MITRE ATT&CK mapping, and structured investigation reports.

| Simulation | Category | Key Finding |
|------------|----------|-------------|
| [Network Reconnaissance via Nmap](https://github.com/Adam-KD/soc-simulations/blob/main/simulations/01-nmap-recon/report.md) | Reconnaissance | Wazuh and Sysmon have zero visibility into network-level scanning - IDS required |
| [RDP Brute Force Attack & Detection](https://github.com/Adam-KD/soc-simulations/blob/main/simulations/02-rdp-brute-force/report.md) | Credential Access | Detection is speed-dependent; NLA bypassed via NTLM fallback; full kill chain captured |
| [Privilege Escalation via Always Install Elevated](https://github.com/Adam-KD/soc-simulations/blob/main/simulations/03-priv-esc/report.md) | Privilege Escalation | Standard user escalated to SYSTEM via GPO misconfiguration; default Wazuh config blind to the entire attack - Sysmon ingestion and FIM tuning required for detection |

### [SQL Security Investigations](https://github.com/Adam-KD/sql-soc)
Simulated attack scenario investigations using SQLite. Covers brute force authentication attacks and DNS-based data exfiltration. Each investigation includes threat intel enrichment via multi-table JOINs, beaconing detection using window functions (LAG), and a full findings report with IOCs, timeline, and recommendations.

### [IOC Extractor - Python](https://github.com/Adam-KD/ioc-extractor)
CLI tool that parses threat reports and extracts IPs, domains, file hashes (MD5/SHA1/SHA256), emails, and CVE IDs via regex. Handles defanged IOCs automatically. Enriches indicators via AbuseIPDB, VirusTotal, and NVD. Outputs to terminal, JSON, CSV, or SQLite for persistent cross-report querying.

### [Ghostwave](https://github.com/Adam-KD/ghostwave) *(In Development)*
Open-source handheld RF signal recorder and replayer built on ESP32 + CC1101. Captures, stores, and replays 433MHz signals with a built-in display interface.

---

## Skills

`SIEM (Wazuh · Splunk · Sentinel)` `Threat Detection & Triage` `Log Analysis` `MITRE ATT&CK`
`Network Traffic Analysis` `Protocol Analysis (RDP · SMB · TLS)` `Wireshark` `Burp Suite`
`Python` `SQL` `Bash` `PowerShell`

---

## Certifications

- **CompTIA Security+** — April 2026
- **SOC Analyst & Web Application Security** — ICS College, 2025–2026
- **TryHackMe SOC Level 1** — Top 2% globally · 100+ labs · March 2026
- **CCNA** — Cisco, In Progress

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-adam--kd-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/adam-kd)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-AdamKD-212C42?style=flat&logo=tryhackme)](https://tryhackme.com/p/AdamKD)
[![Email](https://img.shields.io/badge/Email-adamkd.cyber@gmail.com-D14836?style=flat&logo=gmail)](mailto:adamkd.cyber@gmail.com)
