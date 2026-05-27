# Security Policies

## Purpose
This document outlines security hardening policies configured through Group Policy.

---

# Policies Implemented

- Disable Guest Account
- Enable Windows Defender
- Enable Windows Firewall
- Disable SMBv1
- Enable Audit Logging
- Enable PowerShell Logging

---

# GPO Information

| Setting | Value |
|---|---|
| GPO Name | Security Policies |

---

# GPO Paths

## Firewall

```text
Computer Configuration
→ Policies
→ Windows Settings
→ Security Settings
→ Windows Defender Firewall
```

---

## Audit Policies

```text
Computer Configuration
→ Policies
→ Windows Settings
→ Security Settings
→ Advanced Audit Policy Configuration
```

---

# Configuration Steps

1.
2.
3.

---

# Validation

## Commands Used

```powershell
Get-NetFirewallProfile
auditpol /get /category:*
```

---

# Screenshots

## Firewall Configuration
(Add screenshot here)

## Audit Policies
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
