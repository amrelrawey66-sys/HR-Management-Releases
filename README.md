# HR & Corporate Compliance Manager (CCM) — Official Releases

**Developer & Copyright Owner:** Amr Al.Rawey (*Software Developer & System Designer*)  
**Copyright © 2026 Amr Al.Rawey. All rights reserved.**  
**Designed & Developed by Amr Al.Rawey.**

> This repository hosts **official compiled Windows installers, digitally signed update manifests, SHA-256 checksums, and release notes only**. Source code is proprietary and maintained privately.

---

## Direct Download (No GitHub Account Required)

- **Latest Stable Windows Installer (`CCM_Setup.exe`):**  
  https://github.com/amrelrawey66-sys/HR-Management-Releases/releases/latest/download/CCM_Setup.exe
- **All Official Releases & Release Notes:**  
  https://github.com/amrelrawey66-sys/HR-Management-Releases/releases/latest

---

## System Requirements & Installation Instructions

1. **Operating System:** Windows 10 or Windows 11 (64-bit, `x64`).
2. Download **`CCM_Setup.exe`** from the direct link above.
3. Run **`CCM_Setup.exe`** and choose:
   - **Complete All-in-One** *(Recommended for standalone PCs — installs Desktop Client + Local HTTPS API + Automatic Email Notification Service)*.
   - **Desktop Client Workstation Only** *(Connects to a central company server on your LAN)*.
   - **Central Company Server Only** *(Installs Central HTTPS API + Email Notification Service + SQL Server deployment script)*.
4. Existing upgrades preserve all local databases (`ccm.db`), archived PDF documents, user accounts, email credentials, weekly schedules, and theme/language preferences automatically.

---

## Automatic Updates & Cryptographic Verification

- Every installed copy of CCM checks this official release channel automatically on startup and periodically in the background — no GitHub sign-in required.
- Every release includes:
  - `CCM_Setup.exe` — Production Windows 64-bit installer (compiled with ReadyToRun, zero debug symbols).
  - `SHA256SUMS.txt` — Cryptographic SHA-256 checksum for manual or automated verification.
  - `release-manifest.json` — Official semantic version & integrity metadata.
  - `release-manifest.sig` — **RSA-4096-PSS-SHA256** digital signature verified directly by the application before any update is accepted.
- Modified, tampered, or unsigned update packages are automatically rejected.

---

## License & Intellectual Property

**Copyright © 2026 Amr Al.Rawey. All rights reserved.**  
**Designed & Developed by Amr Al.Rawey.**

This software is proprietary and governed by [LICENSE.txt](LICENSE.txt). Unauthorized copying, modification, reverse engineering, resale, or redistribution is prohibited except as permitted by applicable law. Required open-source acknowledgments are preserved in [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md).
