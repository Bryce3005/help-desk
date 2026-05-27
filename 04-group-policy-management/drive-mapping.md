# Drive Mapping Policy

## Purpose
This document outlines the network drive mapping configuration deployed through Group Policy.

---

# Drive Mappings

| Drive Letter | Path | Purpose |
|---|---|---|
| H: | \\fileserver\home | Home Folders |
| S: | \\fileserver\shared | Shared Files |

---

# GPO Information

| Setting | Value |
|---|---|
| GPO Name | Drive Mapping Policy |
| Linked OU | Users |

---

# GPO Path

```text
User Configuration
→ Preferences
→ Windows Settings
→ Drive Maps
```

---

# Security Filtering

| Group | Access |
|---|---|
| HR_Users | HR Drive |
| IT_Users | IT Drive |

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
net use
```

---

# Screenshots

## Drive Maps Configuration
(Add screenshot here)

## Client Mapped Drives
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
