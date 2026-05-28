
---

# `ticket-17-unauthorized-software.md`

# Ticket 17 - Unauthorized Software Installed

## Ticket Information
- **Ticket ID:** SEC-017
- **Priority:** Medium
- **Category:** Software Compliance
- **Status:** Resolved

---

## User Issue
Unauthorized or unapproved software was discovered on a company workstation.

---

## Environment
- Windows Domain Environment
- Managed Endpoint Devices
- Active Directory

---

## Symptoms
- Unknown application installed
- Security policy violation
- Excessive resource usage
- Unapproved remote access or gaming software

---

## Troubleshooting Steps
1. Identified unauthorized application
2. Verified software against approved software policy
3. Uninstalled unauthorized software
4. Scanned system for additional threats
5. Checked installation source
6. Verified user permissions
7. Documented incident
8. Applied software restriction policies if needed

---

## Resolution
Unauthorized software removed and endpoint brought back into compliance.

---

## Root Cause
User installed software without administrative approval.

---

## Tools Used
- Control Panel / Apps & Features
- Group Policy Management
- Microsoft Defender
- PowerShell

---

## Commands / Tools
```powershell
Get-WmiObject Win32_Product
appwiz.cpl
