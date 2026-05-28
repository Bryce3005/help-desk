# Ticket 06 - No Internet Connection

## Ticket Information
- **Ticket ID:** HD-006
- **Priority:** High
- **Category:** Network Connectivity
- **Status:** Resolved
- **Reported By:** [Username]
- **Assigned To:** [Your Name]
- **Date Opened:** [Date]
- **Date Resolved:** [Date]

---

## User Issue
User reports they cannot access the internet or company resources.

---

## Environment
- Windows 10/11
- Domain Network
- Ethernet/Wi-Fi Connection
- pfSense / Router / Switch Infrastructure

---

## Symptoms
- No internet access
- Websites fail to load
- Teams/Outlook disconnected
- Yellow warning icon on the network adapter

---

## Troubleshooting Steps
1. Verified physical network connection
2. Checked network adapter status
3. Confirmed IP address assignment
4. Tested connectivity using ping
5. Restarted the network adapter
6. Renewed DHCP lease
7. Restarted workstation
8. Tested internet access successfully

---

## Resolution
Restored internet connectivity after renewing the DHCP lease and restarting the network adapter.

---

## Root Cause
The network adapter lost connectivity or failed to receive a valid network configuration.

---

## Commands / Tools Used
```powershell
ipconfig /release
ipconfig /renew
ping 8.8.8.8
ipconfig /all
