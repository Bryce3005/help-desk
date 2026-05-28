# Ticket 07 - macOS Printer Not Working

## Ticket Information
- **Ticket ID:** MAC-007
- **Priority:** Medium
- **Category:** Printing / Hardware
- **Status:** Resolved
- **Reported By:** [Username]
- **Assigned To:** [Your Name]
- **Date Opened:** [Date]
- **Date Resolved:** [Date]

---

## User Issue
User unable to print from macOS device to network or local printer.

---

## Environment
- macOS Sonoma / Ventura / Monterey
- Network Printer / USB Printer
- Corporate Wi-Fi or Ethernet Network
- Print Server Environment

---

## Symptoms
- Printer appears offline
- Print jobs stuck in queue
- “Unable to connect to printer” message
- Printer missing from printer list
- Slow or failed print jobs

---

## Troubleshooting Steps
1. Verified printer power and network connectivity
2. Checked printer status on macOS
3. Cleared stuck print queue
4. Removed and re-added printer
5. Verified correct printer drivers
6. Restarted printer and Mac
7. Tested print from another application
8. Confirmed successful print job

---

## Resolution
Printer functionality restored after clearing print queue and reinstalling printer connection.

---

## Root Cause
Corrupted print queue or network communication issue with printer.

---

## Commands / Tools Used
```bash
lpstat -p
cancel -a
