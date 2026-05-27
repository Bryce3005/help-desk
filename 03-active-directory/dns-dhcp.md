# DNS & DHCP Configuration

## Purpose
This document outlines the DNS and DHCP configuration used in the Help Desk Homelab environment.

---

# Environment

| Component | Value |
|---|---|
| Domain Name | brycefalker.com |
| Domain Controller | DC01 |
| Server IP | 172.16.0.10 |
| DHCP Scope | 172.16.0.100 - 172.16.0.200 |

---

# DNS Configuration

## Forward Lookup Zone
- Zone Name: brycefalker.com
- Type: Active Directory-Integrated Primary
- Replication Scope: All DNS servers in this domain

## DNS Records

| Record Type | Name | IP Address |
|---|---|---|
| A | dc01 | 172.16.0.10 |
| A | osTicket | 172.16.0.102 |
| A | Workstation1 | 172.16.0.100 |
| A | Workstation2 | 172.16.0.101 |
---

# DHCP Configuration

## Scope Information

| Setting | Value |
|---|---|
| Scope Name | 172.16.0.100 - 172.16.0.200 |
| IP Range | 172.16.0.100 - 172.16.0.200 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 172.16.0.10 |
| DNS Server | 172.16.0.10 |
| Lease Duration | 8 days |

---

# Reservations

| Device | IP Address |
|---|---|
| osTicket Server | 172.16.0.102 |


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
