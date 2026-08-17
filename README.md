# CISA XP Cyber Range Challenge Documentation  
![CISA](https://img.shields.io/badge/CISA-Cybersecurity%20%26%20Infrastructure%20Security%20Agency-003366?style=for-the-badge&logo=shield&logoColor=white)

Personal documentation of Cybersecurity and Infrastructure Security Agency (CISA) challenges completed on the XP Cyber Range. These labs highlight vulnerabilities and security misconfigurations encountered in production environments.

---

**Vulnerability Exploitation**
* **Papercut PrintMeShells** (CVE-2023-27350) — [View Writeup](./vulnerabilities/CVE-2023-27350.md)
* **Cacti Anonymous Polling** (CVE-2022-46169) — [View Writeup](./vulnerabilities/CVE-2022-46169.md)
* **ForgeRock OpenAM Backstage Pass** (CVE-2021-35464) — [View Writeup](./vulnerabilities/CVE-2021-35464.md)
* **Baron Samedit** (CVE-2021-3156) — [View Writeup](./vulnerabilities/CVE-2021-3156.md)

**OT / ICS Security**
* **Exposed Public HMI** (Internet exposure & access controls) — [View Writeup](./ot-ics/exposed-hmi.md)
* **Exposed CCTV Cameras** (Public feed hardening) — [View Writeup](./ot-ics/exposed-cctv.md)
* **VPN Credential Stuffing** (Pivoting into HMI controls) — [View Writeup](./ot-ics/vpn-credential-stuffing.md)
* **Historian Data Backups** (Exposed endpoints & failed jobs) — [View Writeup](./ot-ics/historian-backups.md)

**Linux Administration & Helpdesk**
* **Linux User & Service Management** (Users, groups & upgrades) — [View Writeup](./sysadmin/linux-user-service-management.md)
* **Linux Hardening** (SSH access, membership & patching) — [View Writeup](./sysadmin/linux-ssh-hardening.md)
* **Helpdesk Support** (Windows workstation troubleshooting) — [View Writeup](./sysadmin/windows-workstation-troubleshooting.md)

---

**Directory Structure**
```text
├── README.md
├── vulnerabilities/ (CVE-2021-3156.md, CVE-2021-35464.md, CVE-2022-46169.md, CVE-2023-27350.md)
├── ot-ics/          (exposed-cctv.md, exposed-hmi.md, historian-backups.md, vpn-credential-stuffing.md)
└── sysadmin/        (linux-ssh-hardening.md, linux-user-service-management.md, windows-workstation-troubleshooting.md)
