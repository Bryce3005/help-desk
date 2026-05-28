# Ticket 03 - macOS Wi-Fi Connected but No Internet

## Ticket Information
- **Ticket ID:** MAC-003
- **Priority:** Medium
- **Category:** Network Connectivity
- **Status:** Resolved
- **Reported By:** [Username]
- **Assigned To:** [Your Name]
- **Date Opened:** [Date]
- **Date Resolved:** [Date]

---

## User Issue
User reports Mac is connected to Wi-Fi but cannot access the internet or company resources.

---

## Environment
- macOS Sonoma / Ventura / Monterey
- Corporate Wi-Fi Network
- DHCP / DNS Infrastructure
- pfSense / Router / Access Point

---

## Symptoms
- Wi-Fi icon shows connected
- Websites fail to load
- Teams/Outlook offline
- DNS lookup failures
- “No Internet Connection” warning

---

## Troubleshooting Steps
1. Verified Wi-Fi connection status
2. Tested internet access with browser
3. Checked IP address assignment
4. Verified DNS server configuration
5. Renewed DHCP lease
6. Forgot and rejoined Wi-Fi network
7. Restarted networking services
8. Tested successful connectivity

---

## Resolution
Internet access restored after renewing DHCP lease and correcting DNS settings.

---

## Root Cause
Invalid DNS configuration or stale DHCP lease prevented internet access.

---

## Commands / Tools Used
```bash
ifconfig
ping 8.8.8.8
networksetup -getdnsservers Wi-Fi
sudo dscacheutil -flushcache
