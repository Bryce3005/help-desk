
---

# `ticket-14-audio-not-working.md`

# Ticket 14 - Audio Not Working

## Ticket Information
- **Ticket ID:** HW-014
- **Priority:** Low
- **Category:** Hardware / Audio
- **Status:** Resolved

---

## User Issue
User reports no sound from speakers or headset.

---

## Environment
- Windows 10/11
- USB / Bluetooth / Built-in Audio Devices
- Company Workstation or Laptop

---

## Symptoms
- No audio output
- Muted speaker icon
- Audio device missing
- Microphone not detected
- Teams/Zoom audio failure

---

## Troubleshooting Steps
1. Verified volume and mute settings
2. Checked default playback device
3. Reconnected headset/speakers
4. Restarted Windows Audio service
5. Updated/reinstalled audio drivers
6. Tested alternate audio device
7. Restarted workstation
8. Verified audio functionality

---

## Resolution
Audio restored after correcting playback device and restarting audio services.

---

## Root Cause
Incorrect playback device selection or driver/service issue.

---

## Commands / Tools Used
```powershell
services.msc
mmsys.cpl
