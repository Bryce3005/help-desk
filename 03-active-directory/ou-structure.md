# Organizational Unit (OU) Structure

## Purpose
This document outlines the Active Directory Organizational Unit structure used in the homelab environment.

---

# Environment

| Component | Value |
|---|---|
| Domain | brycefalker.com |
| Domain Controller | DC01 |

---

# OU Structure

```text
brycefalker.com
├── Builtin
├── Computers
├── Domain Controllers
├── ForeignSecurityPrincipals
├── Managed Service Accounts
├── Servers
├── User Accounts
  ├── Admins
  ├── Executives
  ├── Finance
  ├── HR
  ├── IT
  ├── Sales
├── Workstations
```

---

# OU Breakdown

## OU Users Accounts
Purpose:
- Stores company OU's containing user accounts

## OUs in Users Accounts
- Admins
- Disabled Users
- Executives
- Finance
- HR
- IT
- Sales

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

# Validation

## Tools Used
- Active Directory Users and Computers

---

# Screenshots

## OU Structure
(Add screenshot here)

---

# Lessons Learned
-
-
-
