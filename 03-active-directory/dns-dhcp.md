# DNS & DHCP Configuration

## Purpose
This document outlines the DNS and DHCP configuration used in the Help Desk Homelab environment.

---

# Environment

| Component | Value |
|---|---|
| Domain Name | homelab.local |
| Domain Controller | DC01 |
| Server IP | 192.168.1.10 |
| DHCP Scope | 192.168.1.100 - 192.168.1.200 |

---

# DNS Configuration

## Forward Lookup Zone
- Zone Name:
- Type:
- Replication Scope:

## Reverse Lookup Zone
- Network ID:
- PTR Records Configured:

## DNS Records

| Record Type | Name | IP Address |
|---|---|---|
| A | dc01 | 192.168.1.10 |
| A | fileserver | 192.168.1.20 |

---

# DHCP Configuration

## Scope Information

| Setting | Value |
|---|---|
| Scope Name | |
| IP Range | |
| Subnet Mask | |
| Default Gateway | |
| DNS Server | |
| Lease Duration | |

---

# Reservations

| Device | IP Address |
|---|---|
| Printer | |
| Server | |

---

# Configuration Steps

## DNS Setup
1.
2.
3.

## DHCP Setup
1.
2.
3.

---

# Validation

## Commands Used

```powershell
ipconfig /all
nslookup dc01
ping homelab.local
```

---

# Troubleshooting

## Issue
Describe issue here.

## Cause
Describe root cause.

## Resolution
Describe fix.

---

# Screenshots

## DNS Manager
(Add screenshot here)

## DHCP Scope
(Add screenshot here)

---

# Lessons Learned
- 
- 
- 
