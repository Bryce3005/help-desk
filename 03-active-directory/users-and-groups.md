# Users & Groups

## Purpose
This document outlines user account and security group management within the homelab environment.

---

# User Accounts

## Naming Convention

```text
First Initial + Last Name
Example: jsmith
```

---

# Example Users

| Username | Department | Role |
|---|---|---|
| jsmith | HR | HR Specialist |
| mjohnson | IT | Help Desk Technician |

---

# Security Groups

| Group Name | Purpose |
|---|---|
| VPN_Users | VPN Access |
| HR_Share_RW | HR Shared Folder Access |
| HelpDesk_Admins | Help Desk Permissions |

---

# Group Scope

## Global Groups
Purpose:
-

## Domain Local Groups
Purpose:
-

---

# Permissions Mapping

| Group | Resource |
|---|---|
| HR_Share_RW | HR Shared Drive |
| VPN_Users | VPN Access |

---

# Account Management Tasks

## Password Reset
1.
2.
3.

## Unlock Account
1.
2.
3.

## Add User to Group
1.
2.
3.

---

# Validation

## Commands Used

```powershell
whoami /groups
net user username /domain
```

---

# Screenshots

## User Accounts
(Add screenshot here)

## Security Groups
(Add screenshot here)

---

# Lessons Learned
-
-
-
