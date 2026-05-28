# 01 - Domain Controller Setup

## Objective
Build and configure a Windows Server Domain Controller for the help desk homelab environment.

---

# Environment Information

| Component | Value |
|---|---|
| Hypervisor | VirtualBox |
| Server OS | Windows Server 2022 |
| Hostname | DC01 |
| Domain Name | homelab.local |
| IP Address | 192.168.1.10 |
| RAM | 4-8 GB |
| CPU | 2 vCPUs |

---

# VM Configuration

## VirtualBox Settings
- Generation: [N/A]
- Network Adapter: Bridged / Internal Network
- Storage Size: 60 GB
- ISO Used: Windows Server 2022 ISO

---

# Windows Server Installation

## Steps
1. Create new VM
2. Attach Windows Server ISO
3. Configure RAM/CPU
4. Install Windows Server
5. Set Administrator password
6. Configure static IP address
7. Rename computer to DC01
8. Restart server

---

# Static IP Configuration

| Setting | Value |
|---|---|
| IP Address | 192.168.1.10 |
| Subnet Mask | 255.255.255.0 |
| Gateway | 192.168.1.1 |
| DNS Server | 192.168.1.10 |

---

# Active Directory Installation

## Roles Installed
- Active Directory Domain Services
- DNS Server
- DHCP Server

---

## PowerShell Commands

```powershell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
