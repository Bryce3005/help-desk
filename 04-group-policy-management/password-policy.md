# Password Policy

## Purpose
This document outlines the domain password and account lockout policies configured in Active Directory.

---

# Password Policy Settings

| Setting | Value |
|---|---|
| Minimum Password Length | 12 |
| Complexity Requirements | Enabled |
| Password History | 24 Passwords |
| Maximum Password Age | 90 Days |

---

# Account Lockout Policy

| Setting | Value |
|---|---|
| Lockout Threshold | 5 Attempts |
| Lockout Duration | 15 Minutes |
| Reset Counter After | 15 Minutes |

---

# GPO Information

| Setting | Value |
|---|---|
| GPO Name | Default Domain Policy |

---

# GPO Path

```text
Computer Configuration
→ Policies
→ Windows Settings
→ Security Settings
→ Account Policies
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
gpresult /r
net accounts
```

---

# Screenshots

## Password Policy
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
