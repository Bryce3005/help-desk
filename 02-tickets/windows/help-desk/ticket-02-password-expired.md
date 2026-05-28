
---

# `ticket-02-password-expired.md`

```md
# Ticket 02 - Password Expired

## Ticket Information
- **Ticket ID:** HD-002
- **Priority:** Medium
- **Category:** Password Management
- **Status:** Resolved

---

## User Issue
User cannot log in because their password expired.

---

## Environment
- Windows Domain Environment
- Microsoft 365 synced accounts
- Active Directory

---

## Symptoms
- “Your password has expired” message
- Unable to access Outlook or Teams
- Login loop

---

## Troubleshooting Steps
1. Verified password expiration in AD
2. Reset password in Active Directory
3. Forced password change at next login
4. Synced password to Microsoft 365
5. Confirmed successful login

---

## Resolution
Password reset completed and user regained access.

---

## Root Cause
Password exceeded domain expiration policy.

---

## Tools Used
- Active Directory Users and Computers
- Microsoft 365 Admin Center
- Azure/Entra Connect

---

## Screenshots
```md
![Password Reset](./screenshots/password-reset.png)
