
# 02 - Network Setup

## Objective
Configure the homelab network infrastructure and connectivity.

---

# Network Topology

## Devices
- Domain Controller

---

# IP Addressing Scheme

| Device | IP Address |
|---|---|
| DC01 | 172.16.0.10 |

---

# DHCP Configuration

## DHCP Scope
- Start Range: 172.16.0.100
- End Range: 172.16.0.200
- Lease Duration: 8 Days

---

# DNS Configuration

## DNS Server
- Primary DNS: 172.16.0.10

---

# Routing Configuration

## NAT
- The Internet NIC acts as the router
  - One IP address is used to connect to the internet for all devices

---

## Commands
```powershell
ping dc01
ipconfig /all
nslookup homelab.local
