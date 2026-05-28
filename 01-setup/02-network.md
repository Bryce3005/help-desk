
# 02 - Network Setup

## Objective
Configure the homelab network infrastructure and connectivity.

---

# Network Topology

## Devices
- Domain Controller
- Windows Clients
- macOS Client
- pfSense Firewall
- Switch
- Router

---

# IP Addressing Scheme

| Device | IP Address |
|---|---|
| DC01 | 192.168.1.10 |
| pfSense | 192.168.1.1 |
| Windows Client | DHCP |
| macOS Client | DHCP |

---

# DHCP Configuration

## DHCP Scope
- Start Range: 192.168.1.100
- End Range: 192.168.1.200
- Lease Duration: 8 Days

---

# DNS Configuration

## DNS Server
- Primary DNS: 192.168.1.10

---

# VLANs (Optional)

| VLAN | Purpose |
|---|---|
| 10 | Servers |
| 20 | Workstations |
| 30 | Management |

---

# Connectivity Testing

## Commands

```powershell
ping dc01
ipconfig /all
nslookup homelab.local
