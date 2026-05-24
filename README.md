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

---

## Lab Environment

- **Host:** AMD Ryzen 7 5700G · 32GB RAM · Windows 11 Pro
- **Hypervisor:** VMware Workstation
- **VMs:** Ubuntu Server, Kali Linux, Windows 10, Windows Server 2019
- **Stack:** Wazuh · OpenSearch · Shuffle SOAR · Docker · Qualys VMDR · ModSecurity

---

## Tools & Frameworks

`Qualys VMDR` `Wazuh` `ModSecurity` `OWASP CRS` `Shuffle SOAR` `Docker`  
`Nmap` `Hydra` `SQLMap` `Burp Suite` `Metasploit`  
`NIST CSF` `PCI DSS` `MITRE ATT&CK` `ISO 27001` `CIS Controls`
