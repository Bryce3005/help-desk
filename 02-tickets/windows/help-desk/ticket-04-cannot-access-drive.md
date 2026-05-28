
---

# `ticket-04-cannot-access-drive.md`

# Ticket 04 - Cannot Access Network Drive

## Ticket Information
- **Ticket ID:** HD-004
- **Priority:** Medium
- **Category:** File Share / Permissions
- **Status:** Resolved

---

## User Issue
User cannot access mapped network drive.

---

## Environment
- Windows Domain Environment
- File Server
- Shared Network Drives

---

## Symptoms
- Access denied message
- Network drive disconnected
- Missing mapped drive

---

## Troubleshooting Steps
1. Verified network connectivity
2. Checked shared folder permissions
3. Confirmed NTFS permissions
4. Verified user group membership
5. Remapped network drive
6. Restarted workstation

---

## Resolution
Updated permissions and remapped the drive successfully.

---

## Root Cause
Incorrect permissions or disconnected mapped drive.

---

## Commands / Tools Used
```powershell
net use Z: \\fileserver\sharedfolder
