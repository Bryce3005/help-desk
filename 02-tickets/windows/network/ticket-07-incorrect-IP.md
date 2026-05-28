
---

# `ticket-07-incorrect-IP.md`

# Ticket 07 - Incorrect IP Address

## Ticket Information
- **Ticket ID:** HD-007
- **Priority:** Medium
- **Category:** DHCP / IP Configuration
- **Status:** Resolved

---

## User Issue
User workstation received an incorrect IP address and could not connect to network resources.

---

## Environment
- Windows Domain Environment
- DHCP Server
- VLAN/Subnet Infrastructure

---

## Symptoms
- APIPA address (169.254.x.x)
- Unable to reach domain resources
- No internet connectivity
- DNS resolution failures

---

## Troubleshooting Steps
1. Checked current IP configuration
2. Verified DHCP server availability
3. Released and renewed IP address
4. Confirmed correct VLAN assignment
5. Verified DNS server settings
6. Restarted network adapter
7. Tested connectivity successfully

---

## Resolution
Assigned correct IP configuration from DHCP server.

---

## Root Cause
DHCP communication failure or incorrect VLAN/network configuration.

---

## Commands / Tools Used
```powershell
ipconfig /all
ipconfig /release
ipconfig /renew
nslookup google.com
