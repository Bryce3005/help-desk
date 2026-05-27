# Organizational Unit (OU) Structure

## Purpose
This document outlines the Active Directory Organizational Unit structure used in the homelab environment.

---

# Environment

| Component | Value |
|---|---|
| Domain | homelab.local |
| Domain Controller | DC01 |

---

# OU Structure

```text
homelab.local
├── Users
├── Workstations
├── Servers
├── Groups
├── IT
├── HR
├── Sales
└── Admins
```

---

# OU Breakdown

## Users OU
Purpose:
- Stores standard user accounts

Applied GPOs:
- User Restrictions
- Drive Mapping

---

## Workstations OU
Purpose:
- Stores all domain-joined computers

Applied GPOs:
- Windows Update Policy
- Workstation Policies

---

## Servers OU
Purpose:
- Stores Windows Servers

Applied GPOs:
- Security Policies

---

# Delegation

| Group | Permission |
|---|---|
| HelpDesk_Admins | Reset Passwords |
| IT_Admins | Full Control |

---

# Configuration Steps

1.
2.
3.

---

# Validation

## Tools Used
- Active Directory Users and Computers
- Group Policy Management

---

# Screenshots

## OU Structure
(Add screenshot here)

---

# Lessons Learned
-
-
-
