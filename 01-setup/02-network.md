# Network Setup

## Objective

This networking setup is designed to host servers and workstations and connect all devices to the domain network brycefalker.com. 

---

# Environment Information

| Item | Value |
|---|---|
| Server Name | DC01 |
| OS | Windows Server 2022 |
| IP Address | 172.16.0.10 |
| Role | Domain Controller |

---

# Prerequisites

- Creation of the domain controller machine
  
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

- Pinged a DNS Server in the command prompt
   - 8.8.8.8
- Used ipconfig /all in the command prompt
   - IP address for the internal NIC should be 172.16.0.10
   -  IP address for the internet NIC should start with a 10
- Open Microsoft Edge and see if you can access a website

---

# Troubleshooting

Document problems encountered and solutions.

| Issue | Solution |
|---|---|
| IP address didn't switch after changing it | Released the IP and renewed it |
| Couldn't connect to any websites | Switched both dns addresses for the NICs to 172.16.0.10 the domain controller IP |

---

# Skills Demonstrated

- Network Administration
- Troubleshooting
- DNS Configuration
- DHCP Management
- Routing configuration

---

# Lessons Learned

Example:
I learned how the DNS configuration directly impacts website and domain connectivity. The importance of having a DHCP server with a scope to give devices in the domain specified IP addresses. Routing and why it's necessary to add NAT, so the users in the domain can access the internet with one address. 
