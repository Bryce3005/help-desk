
---

# `ticket-16-antivirus-alert.md`

# Ticket 16 - Antivirus Alert Detected

## Ticket Information
- **Ticket ID:** SEC-016
- **Priority:** High
- **Category:** Endpoint Security
- **Status:** Resolved

---

## User Issue
Antivirus software detected suspicious or malicious activity on the workstation.

---

## Environment
- Windows 10/11
- Microsoft Defender / Antivirus Platform
- Domain Environment

---

## Symptoms
- Antivirus pop-up alert
- Threat detected notification
- Quarantined file warning
- Slow system performance
- Possible malicious process activity

---

## Troubleshooting Steps
1. Identified threat name and severity
2. Isolated workstation from network if necessary
3. Performed full antivirus scan
4. Removed/quarantined malicious files
5. Reviewed startup programs and processes
6. Checked browser extensions/downloads
7. Installed latest antivirus definitions
8. Verified system clean after rescan

---

## Resolution
Threat removed successfully and workstation secured.

---

## Root Cause
User downloaded or executed malicious/suspicious content.

---

## Tools Used
- Microsoft Defender
- Task Manager
- Event Viewer
- Endpoint Detection & Response (EDR)

---

## Commands / Tools
```powershell
Start-MpScan -ScanType FullScan
Get-MpThreat
