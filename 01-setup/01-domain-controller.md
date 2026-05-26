# Domain Controller Setup

## Objective

A Domain Controller is used to authenticate users, enforce security policies, and manage resource access.

---

# Environment Information

| Item | Value |
|---|---|
| Server Name | DC01 |
| OS | Windows Server 2025 |
| IP Address | 172.16.0.10 |
| Role | Domain Controller |

---

# Prerequisites

- VirtualBox Downloaded

---

# Installation Steps

Step-by-step deployment process.

### Install Server Role

1. Open VirtualBox
2. Left-click the new button
3. Enter:
   - The name of the machine (DC01)
   - The ISO Image
   - OS Edition
   - 

---

# Configuration Steps

Document important configurations.

Examples:
- OU structure
- GPOs
- DNS settings
- Ticket departments
- Sync options

---

# Validation / Testing

Show how you verified functionality.

Examples:
- Successful domain join
- User synced to Microsoft 365
- Ticket submission successful
- GPO applied correctly

---

# Troubleshooting

Document problems encountered and solutions.

| Issue | Solution |
|---|---|
| DNS resolution failed | Corrected preferred DNS server |
| Entra sync failed | Restarted sync service |

This section is HUGE for recruiters.

---

# Security Considerations

Document security-related configurations.

Examples:
- Strong passwords enforced
- Least privilege groups used
- Firewall enabled
- MFA enabled in Microsoft 365

---

# Screenshots

Add screenshots showing:
- Installation
- Configuration
- Successful deployment

Example:

```md
![Domain Controller](../screenshots/active-directory/server-manager.png)
```

---

# Skills Demonstrated

- Windows Administration
- Troubleshooting
- DNS Configuration
- Identity Management
- Group Policy

---

# Lessons Learned

Explain what you learned during deployment.

Example:
I learned how DNS configuration directly impacts Active Directory authentication and workstation communication.
