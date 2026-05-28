
# 08 - macOS Active Directory Integration

## Objective
Bind macOS devices to Active Directory and test authentication.

---

# Environment

| Component | Value |
|---|---|
| macOS Version | Sonoma / Ventura |
| Domain | homelab.local |
| Domain Controller | DC01 |

---

# Prerequisites

- Internal DNS configured
- Time synchronization working
- Domain admin credentials available

---

# AD Binding Steps

1. Open Directory Utility
2. Select Active Directory
3. Enter domain information
4. Authenticate with domain admin
5. Apply settings
6. Restart Mac

---

# Commands

```bash
dsconfigad -show
sudo dsconfigad -add homelab.local
