
# 05 - macOS Setup

## Objective
Configure macOS workstation for homelab integration.

---

# Environment

| Component | Value |
|---|---|
| OS | macOS Sonoma |
| Device Type | Virtual Machine / Mac |

---

# Installation Steps

1. Install macOS
2. Ensure the adapter is set to the internal network
3. Enable remote access
4. Install productivity tools

---

# Network Configuration

## Verify Connectivity

```bash
ifconfig
ping 172.16.0.10
