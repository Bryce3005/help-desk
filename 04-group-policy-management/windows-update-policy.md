# Windows Update Policy

## Purpose
This document outlines Windows Update management configured through Group Policy.

---

# Update Configuration

| Setting | Value |
|---|---|
| Automatic Updates | Enabled |
| Install Schedule | Sunday 3:00 AM |
| Active Hours | 8:00 AM - 5:00 PM |

---

# GPO Information

| Setting | Value |
|---|---|
| GPO Name | Windows Update Policy |

---

# GPO Path

```text
Computer Configuration
→ Policies
→ Administrative Templates
→ Windows Components
→ Windows Update
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
Get-WindowsUpdateLog
```

---

# Screenshots

## Windows Update GPO
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
