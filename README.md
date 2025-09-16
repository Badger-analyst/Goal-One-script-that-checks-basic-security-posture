# Goal-One-script-that-checks-basic-security-posture
practical Windows 10/11 cybersecurity health check script
# 🛡️ Windows Cybersecurity Health Check Script

A simple PowerShell script for **small businesses** to quickly check the cybersecurity health of Windows 10/11 machines.

## ✅ Features
- Checks if the **firewall** is enabled.
- Verifies **antivirus** (Windows Defender or 3rd-party).
- Runs a **quick malware scan** using Windows Defender.
- Flags **suspicious processes** running from unusual locations.
- Provides **recommended firewall ACLs** for inbound/outbound traffic.

## 🚀 Usage
1. Download or clone this repo.
2. Open **PowerShell as Administrator**.
3. Run the script:
   ```powershell
   .\cyber-check.ps1
Notes

Requires Windows PowerShell 5.1+ (default on Windows 10/11).

For best results, run as Administrator.

This is not a replacement for enterprise security tools, but a quick health check.

microsoft-cloud-security-checklist-2025

Inside:

README.md → Markdown checklist (easy for IT staff to use).

(Optional) checklist.ps1 → PowerShell script that pulls Azure Secure Score, checks MFA status, and exports results to CSV.

.gitignore → Standard PowerShell/Windows template.
