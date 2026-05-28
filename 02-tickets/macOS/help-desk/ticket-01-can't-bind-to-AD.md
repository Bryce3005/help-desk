# Ticket 01 - macOS Cannot Bind to Active Directory

## Ticket Information
- **Ticket ID:** MAC-001
- **Priority:** High
- **Category:** macOS / Active Directory
- **Status:** Resolved
- **Reported By:** [Username]
- **Assigned To:** [Your Name]
- **Date Opened:** [Date]
- **Date Resolved:** [Date]

---

## User Issue
The macOS device is unable to bind or connect to the Active Directory domain.

---

## Environment
- macOS Sonoma / Ventura / Monterey
- Active Directory Domain
- Windows Server Domain Controller
- Ethernet/Wi-Fi Network

---

## Symptoms
- “Unable to contact Active Directory domain.”
- Binding process fails
- Domain users are unable to log in
- Directory Utility errors
- Authentication failures

---

## Troubleshooting Steps
1. Verified network connectivity to the domain controller
2. Confirmed DNS server settings point to internal DNS
3. Tested communication with the domain controller
4. Opened Directory Utility
5. Attempted manual AD bind
6. Verified AD credentials and permissions
7. Restarted Mac after binding
8. Tested the domain login successfully

---

## Resolution
Successfully bound a macOS device to Active Directory after correcting the DNS/network configuration.

---

## Root Cause
Incorrect DNS settings prevented the Mac from locating the domain controller.

---

## Commands / Tools Used
```bash
ping dc01.domain.local
dsconfigad -show
sudo dsconfigad -add domain.local
