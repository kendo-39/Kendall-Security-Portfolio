# Kendall Montero — Cybersecurity Portfolio

Blue team operations, vulnerability management, SOC automation, and penetration testing.  
All labs were built and executed on personal infrastructure.

---

## Reports

| Report | Area | Description |
|--------|------|-------------|
| [Vulnerability Management Program — Lab Assessment](./reports/VM_Report_Kendall_Montero.pdf) | Vulnerability Management | Full Qualys VMDR lifecycle: unauthenticated → authenticated → post-hardening. 3 VMs, 706 findings, SOPs, risk exceptions |
| [SOC Homelab — Attack & Detection Report](./reports/SOC_HomeLab_Full_Report_v2.pdf) | SOC / Blue Team | Wazuh SIEM + ModSecurity WAF lab. Phase 1 (no WAF) vs Phase 2 (WAF active). Custom MITRE-mapped detection rules |
| [HTB Silentium — Penetration Test Report](./reports/Silentium_HTB_Pentest_Report.pdf) | Penetration Testing | HackTheBox machine. 4-finding exploit chain: CVE-2025-58434, CVE-2025-59528, CVE-2025-8110. Full root compromise |
| [ATM Security Risk Analysis](./reports/ATM_Analisis_Riesgos_KendallMontero.pdf) | Risk Analysis | Physical + cyber risk analysis of ATM infrastructure. PCI DSS, ISO 27001, NIST CSF alignment |
| [Wireless Pentesting Lab Report](./reports/Wireless_Pentesting_Lab_Report.pdf) | Penetration Testing | Portable wireless security lab on Raspberry Pi 3B+ with Kali Linux. Full WPA2 attack chain: passive recon, deauth frame injection, 4-way handshake capture, and offline credential recovery. Hidden SSID detection, open network traffic analysis, and WPS enumeration using Alfa AWUS1900, aircrack-ng suite, and Kismet |
| [GCP Security Lab — TiloPay](./reports/TiloPay_Lab_Report_EN.pdf) | Cloud Security | GCP lab built for a fintech role: custom VPC, IAM roles, Cloud Armor WAF (OWASP Top 10), Cloud Logging, and Wazuh SIEM integration via Pub/Sub. 100% SQLi and XSS blocked. PCI DSS v4.0 aligned |

---

## Lab Environment

### Primary Lab (SOC / VM / Vuln Management)
- **Host:** AMD Ryzen 7 5700G · 32GB RAM · Windows 11 Pro
- **Hypervisor:** VMware Workstation
- **VMs:** Ubuntu Server · Kali Linux · Windows 10 · Windows Server 2019
- **Stack:** Wazuh · OpenSearch · Shuffle SOAR · Docker · Qualys VMDR · ModSecurity

### Wireless Pentesting Lab
- **Platform:** Raspberry Pi 3B+ · Kali Linux 2026.1 (aarch64) · Headless SSH operation
- **Attack Adapter:** Alfa AWUS1900 — RTL8814AU · 4x5dBi antennas · dual-band 2.4/5GHz
- **Management:** Static IP via eth0 · mDNS (avahi) · SSH from mobile via Shelly app
- **Display:** UCTronics 3.5" HDMI LCD — console monitoring
- **Power:** Anker USB power bank — portable field operation

### GCP Cloud Security Lab
- **Platform:** Google Cloud Platform · Project: tilopay-lab-2026
- **Region:** us-central1 · Load Balancer IP: 8.233.157.231
- **Stack:** VPC · IAM Custom Roles · Cloud Armor WAF · Cloud Logging · Pub/Sub
- **Integration:** Wazuh SIEM (on-premise) via GCP Pub/Sub — hybrid architecture

---

## Tools & Frameworks

**Vulnerability Management**  
`Qualys VMDR` `Nmap` `OpenVAS`

**SOC / Blue Team**  
`Wazuh` `OpenSearch` `Shuffle SOAR` `Docker` `ModSecurity` `OWASP CRS`

**Penetration Testing**  
`aircrack-ng` `airodump-ng` `aireplay-ng` `airmon-ng` `Kismet` `Reaver` `Wash`  
`Metasploit` `Burp Suite` `Hydra` `SQLMap`

**Cloud Security**  
`GCP Compute Engine` `Cloud Armor` `Cloud IAM` `Cloud Logging` `Pub/Sub` `gcloud CLI`

**Analysis & Forensics**  
`Wireshark` `tshark` `Nmap`

**Frameworks & Standards**  
`NIST CSF` `PCI DSS` `MITRE ATT&CK` `ISO 27001` `CIS Controls`