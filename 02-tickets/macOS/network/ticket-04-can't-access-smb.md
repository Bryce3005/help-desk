
# Ticket 04 - macOS Cannot Access SMB Share

## Ticket Information
- **Ticket ID:** MAC-004
- **Priority:** Medium
- **Category:** File Share / SMB
- **Status:** Resolved

---

## User Issue
User unable to connect to shared SMB network drive from macOS device.

---

## Environment
- macOS Sonoma / Ventura / Monterey
- Windows File Server
- Active Directory Environment
- SMB Network Shares

---

## Symptoms
- “Connection failed” message
- Shared drive unavailable
- Authentication prompts repeatedly appear
- Unable to mount SMB share
- Access denied errors

---

## Troubleshooting Steps
1. Verified network connectivity to file server
2. Tested SMB share path manually
3. Confirmed user permissions on share
4. Verified Active Directory authentication
5. Cleared cached credentials
6. Reconnected SMB share manually
7. Restarted Finder if necessary
8. Tested successful file access

---

## Resolution
Restored SMB access after correcting credentials and reconnecting network share.

---

## Root Cause
Authentication or SMB permission issue prevented access to the network share.

---

## Commands / Tools Used
```bash
smbutil view //username@fileserver
ping fileserver.domain.local
