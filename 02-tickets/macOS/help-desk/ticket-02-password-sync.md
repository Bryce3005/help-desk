
---

# `ticket-02-password-sync.md`

# Ticket 02 - macOS Password Sync Issue

## Ticket Information
- **Ticket ID:** MAC-002
- **Priority:** Medium
- **Category:** macOS Authentication
- **Status:** Resolved

---

## User Issue
User changed Active Directory password, but macOS local login password did not sync properly.

---

## Environment
- macOS Domain-Joined Device
- Active Directory
- Mobile User Account
- Microsoft 365 Environment

---

## Symptoms
- Login keychain password mismatch
- Repeated password prompts
- Unable to unlock keychain
- Cached credentials outdated
- Domain login delays

---

## Troubleshooting Steps
1. Verified user password change in Active Directory
2. Confirmed successful domain authentication
3. Logged into Mac with updated credentials
4. Reset login keychain password
5. Updated cached credentials
6. Restarted workstation
7. Tested successful login and keychain access

---

## Resolution
Password synchronization restored after resetting the login keychain and updating cached credentials.

---

## Root Cause
macOS keychain retained the old password after the Active Directory password change.

---

## Commands / Tools Used
```bash
security default-keychain
dsconfigad -show
