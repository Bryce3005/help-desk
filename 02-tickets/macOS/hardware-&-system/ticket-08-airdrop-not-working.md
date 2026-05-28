
# Ticket 08 - macOS AirDrop Not Working

## Ticket Information
- **Ticket ID:** MAC-008
- **Priority:** Low
- **Category:** Wireless Connectivity
- **Status:** Resolved

---

## User Issue
User unable to send or receive files using AirDrop.

---

## Environment
- macOS Sonoma / Ventura / Monterey
- Bluetooth and Wi-Fi Enabled
- Apple Ecosystem Devices

---

## Symptoms
- Devices not appearing in AirDrop
- Transfer stuck on waiting
- AirDrop discovery failure
- “Declined” or failed transfers
- Bluetooth/Wi-Fi connectivity issues

---

## Troubleshooting Steps
1. Verified Wi-Fi and Bluetooth enabled
2. Checked AirDrop visibility settings
3. Restarted Finder
4. Disabled and re-enabled AirDrop
5. Confirmed devices were nearby
6. Restarted Bluetooth service
7. Restarted affected devices
8. Tested successful file transfer

---

## Resolution
AirDrop restored after resetting wireless services and adjusting visibility settings.

---

## Root Cause
Bluetooth/Wi-Fi discovery issue or incorrect AirDrop visibility configuration.

---

## Commands / Tools Used
```bash
sudo pkill bluetoothd
killall Finder
