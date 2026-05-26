# Office365 Setup

## Objective

Explain what this system/service is used for and why it exists in the environment.

Example:
This server was configured to provide centralized identity management for the help desk environment.

---

# Environment Information

| Item | Value |
|---|---|
| Server Name | DC01 |
| OS | Windows Server 2022 |
| IP Address | 192.168.1.10 |
| Role | Domain Controller |

---

# Prerequisites

List requirements before installation.

Example:
- Static IP configured
- Windows Server installed
- Internet connectivity
- Administrator account
- ISO downloaded

---

# Installation Steps

Step-by-step deployment process.

## Example

### Install Server Role

1. Open Server Manager
2. Select Add Roles and Features
3. Install:
   - Active Directory Domain Services
   - DNS Server

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
