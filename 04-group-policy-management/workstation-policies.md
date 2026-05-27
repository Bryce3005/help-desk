# Workstation Policies

## Purpose
This document outlines workstation configuration and security policies deployed through Group Policy.

---

# Policies Applied

- Enable BitLocker
- Enable Firewall
- Configure Remote Desktop
- Configure Power Settings
- Configure Screen Lock Timeout
- Enable PowerShell Remoting

---

# GPO Information

| Setting | Value |
|---|---|
| GPO Name | Workstation Policies |

---

# Device Policies

| Policy | Status |
|---|---|
| USB Restrictions | Enabled |
| Printer Deployment | Enabled |

---

# Login Policies

| Policy | Setting |
|---|---|
| Login Banner | Enabled |
| Auto Lock Timeout | 15 Minutes |

---

# Configuration Steps

1.
2.
3.

---

# Validation

## Commands Used

```powershell
gpresult /r
manage-bde -status
```

---

# Screenshots

## Workstation Policies
(Add screenshot here)

## Client Validation
(Add screenshot here)

---

# Troubleshooting

## Issue
-

## Resolution
-

---

# Lessons Learned
-
-
-
