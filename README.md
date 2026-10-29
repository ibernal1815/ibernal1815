<div align="center">

# Isaiah Bernal

### Malware Analysis · Detection Engineering · Offensive Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isaiah-bernal-707576218/)
[![Security+](https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=flat-square)](https://www.comptia.org/certifications/security)
[![CySA+](https://img.shields.io/badge/CompTIA-CySA%2B-C8202F?style=flat-square)](https://www.comptia.org/certifications/cybersecurity-analyst)
[![ISC2 CC](https://img.shields.io/badge/ISC2-CC-468145?style=flat-square)](https://www.isc2.org/certifications/cc)
![In Progress: PenTest+ & SecurityX](https://img.shields.io/badge/In_Progress-PenTest%2B_%7C_SecurityX-555555?style=flat-square)

</div>

---

Security engineer with a foundation in IT infrastructure, focused on dissecting malicious behavior across Windows internals, volatile memory, network traffic, and endpoint telemetry. My work centers on **malware analysis, detection engineering, DFIR, and offensive security**.

I design isolated virtualization labs using **RHEL, KVM/QEMU, libvirt, and rootless containers** to execute adversary simulations, reverse engineer binaries, and validate detection pipelines. I develop custom **Python** tooling to automate EVTX log normalization, IOC extraction, threat intelligence enrichment, and behavioral analysis.

## Engineering & Research Projects

| Project | Architecture & Focus | Core Stack | Status |
| :--- | :--- | :--- | :---: |
| **[Log Normalizer / IOC Extractor](https://github.com/ibernal1815/log-normalizer)** | Automated EVTX parsing, log normalization, regex IOC extraction, and structured JSON output | Python, `python-evtx`, Regex, `pytest` | ![Complete](https://img.shields.io/badge/Complete-2EA043?style=flat-square) |
| **[Threat Intel Enricher](https://github.com/ibernal1815/threat-intel-enricher)** | Automated IOC enrichment, multi-source verdict scoring, and persistent intelligence storage | Python, VirusTotal API, AbuseIPDB, PostgreSQL | ![Complete](https://img.shields.io/badge/Complete-2EA043?style=flat-square) |
| **[Enterprise Active Directory Lab](https://github.com/ibernal1815/active-directory-lab)** | Tiered domain architecture, GPO hardening, automated PowerShell provisioning, and attack simulation | Windows Server, Active Directory, PowerShell | ![Complete](https://img.shields.io/badge/Complete-2EA043?style=flat-square) |
| **[Python Keylogger with C2](https://github.com/ibernal1815/python-keylogger)** | Low-level keystroke capture, AES-encrypted payload staging, HTTP C2 exfiltration, and unit testing | Python, Flask, AES Cryptography, `pytest` | ![Complete](https://img.shields.io/badge/Complete-2EA043?style=flat-square) |
| **[SQL Security Lab](https://github.com/ibernal1815/sql-security-lab)** | SQL injection exploitation and remediation via parameterized queries, RBAC, and row-level security | Python, Flask, PostgreSQL | ![Complete](https://img.shields.io/badge/Complete-2EA043?style=flat-square) |
| **[Sysmon Detection Lab](https://github.com/ibernal1815/sysmon-sysinternals-detection-lab)** | Adversary emulation mapped to MITRE ATT&CK, high-fidelity Sysmon telemetry, and Sigma rule engineering | Sysmon, Sigma, Elastic, Wazuh, MITRE ATT&CK | ![Active Build](https://img.shields.io/badge/Active_Build-0078D4?style=flat-square) |
| **[Windows Internals Lab](https://github.com/ibernal1815/windows-internals-lab)** | Process/thread structures, virtual memory inspection, persistence mechanics, and kernel/user-mode debugging | Windows, WinDbg, Sysinternals, Sysmon, Volatility | ![Active Build](https://img.shields.io/badge/Active_Build-0078D4?style=flat-square) |
| **[Malware Analysis Lab](https://github.com/ibernal1815/malware-analysis-lab)** | Isolated static/dynamic detonation environment, memory forensics, and custom network emulation | RHEL, KVM/QEMU, `libvirt`, FLARE-VM, REMnux, YARA | ![Migrating to KVM](https://img.shields.io/badge/KVM_Migration-D97706?style=flat-square) |

## Technical Stack

| Domain | Technologies & Tooling |
| :--- | :--- |
| **Malware & DFIR** | FLARE-VM · REMnux · Volatility 3 · WinDbg · YARA · Sysinternals · Wireshark · `python-evtx` |
| **Detection & SIEM** | Sysmon · Sigma · Elastic Stack · Splunk · Wazuh · Suricata · MITRE ATT&CK |
| **Offensive Security** | Burp Suite · Nmap · Metasploit · Active Directory Exploitation · C2 Development |
| **Infrastructure & Virtualization** | RHEL · KVM/QEMU · `libvirt` · Podman · Proxmox · VMware · pfSense · Windows Server |
| **Software Engineering** | Python · PowerShell · Bash · SQL · Flask · PostgreSQL · `pytest` · Git |

## Education

| Degree | Institution | Timeline |
| :--- | :--- | :---: |
| **M.S. Cybersecurity and Information Assurance** | Western Governors University | 2027 (Expected) |
| **B.S. Computer Information Technology** | California State University, Northridge | 2026 |
| **A.S. Cybersecurity & Computer Programming** | Los Angeles Mission College | 2023 – 2024 |

---

<div align="center">

**Analyze the behavior. Understand the system. Build the detection.**

</div>
