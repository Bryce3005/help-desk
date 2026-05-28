
---

# `ticket-08-cannot-reach-DC.md`

# Ticket 08 - Cannot Reach Domain Controller

## Ticket Information
- **Ticket ID:** HD-008
- **Priority:** High
- **Category:** Active Directory / DNS
- **Status:** Resolved

---

## User Issue
Workstation cannot communicate with the domain controller.

---

## Environment
- Windows Server Domain Controller
- Active Directory
- DNS/DHCP Infrastructure
- Domain-Joined Workstation

---

## Symptoms
- Unable to log into domain account
- Group Policy not applying
- “Cannot contact domain controller” message
- Network authentication failures

---

## Troubleshooting Steps
1. Verified workstation network connectivity
2. Checked DNS server configuration
3. Pinged domain controller hostname
4. Verified domain controller services
5. Restarted DNS service if needed
6. Forced Group Policy update
7. Tested domain authentication successfully

---

## Resolution
Corrected DNS settings and restored communication with the domain controller.

---

## Root Cause
Incorrect DNS configuration prevented workstation from locating the domain controller.

---

## Commands / Tools Used
```powershell
ping dc01
nslookup domain.local
gpupdate /force
ipconfig /all
