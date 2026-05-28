
# 04 - Windows Workstation Setup

## Objective
Deploy and configure Windows client workstations.

---

# Environment

| Component | Value |
|---|---|
| OS | Windows 10/11 |
| Domain | homelab.local |

---

# Installation Steps

1. Create workstation VM
2. Install Windows
3. Configure hostname
4. Configure DHCP/static networking
5. Join domain
6. Restart workstation

---

# Domain Join

## Steps
1. Open System Properties
2. Select Domain
3. Enter homelab.local
4. Authenticate with domain admin
5. Restart system

---

# Software Installed

- Google Chrome
- Microsoft Office
- Remote Desktop
- Help Desk Tools

---

# Validation

- Test domain login
- Verify internet access
- Verify GPOs applied

---

# Commands

```powershell
systeminfo
gpupdate /force
