
# 04 - Windows Workstation Setup

## Objective
Deploy and configure Windows client workstations.

---

# Environment

| Component | Value |
|---|---|
| OS | Windows 10/11 |
| Domain | brycefalker.com |

---

# Installation Steps

1. Create workstation VM
2. Ensure that your network adapter is set to Internal Network
3. Install Windows
4. Configure hostname
5. Join the domain
6. Restart workstation

---

# Domain Join

## Steps
1. Open System Properties
2. Select Domain
3. Enter brycefalker.com
4. Authenticate with the domain admin account you created
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
