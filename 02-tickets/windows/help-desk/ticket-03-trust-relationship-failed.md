
---

# ticket-03-trust-relationship-failed.md


# Ticket 03 - Trust Relationship Failed

## Ticket Information
- **Ticket ID:** HD-003
- **Priority:** High
- **Category:** Domain Join Issues
- **Status:** Resolved

---

## User Issue
User receives “The trust relationship between this workstation and the primary domain failed.”

---

## Environment
- Windows 10/11
- Active Directory Domain
- Domain-Joined Workstation

---

## Symptoms
- Unable to log into the domain account
- Trust relationship error message
- Computer authentication failure

---

## Troubleshooting Steps
1. Logged in with local administrator account
2. Verified domain connectivity
3. Removed the computer from the domain
4. Rebooted workstation
5. Rejoined the computer to the domain
6. Restarted the system
7. Verified successful domain login

---

## Resolution
Rejoined the workstation to the domain successfully.

---

## Root Cause
A broken secure channel between the workstation and the domain controller.

---

## Commands / Tools Used
```powershell
Test-ComputerSecureChannel -Repair -Credential domain\administrator
