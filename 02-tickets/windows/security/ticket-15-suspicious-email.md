# Ticket 15 - Suspicious Email Reported

## Ticket Information
- **Ticket ID:** SEC-015
- **Priority:** High
- **Category:** Security / Phishing
- **Status:** Resolved
- **Reported By:** [Username]
- **Assigned To:** [Your Name]
- **Date Opened:** [Date]
- **Date Resolved:** [Date]

---

## User Issue
User reported receiving a suspicious email that requested sensitive information or contained unexpected links/attachments.

---

## Environment
- Microsoft 365
- Outlook Desktop/Web
- Exchange Online
- Endpoint Security Platform

---

## Symptoms
- Suspicious sender address
- Urgent or threatening language
- Unexpected attachment or login link
- Email failed SPF/DKIM/DMARC checks
- Multiple users received a similar email

---

## Troubleshooting Steps
1. Collected email headers
2. Verified sender legitimacy
3. Analyzed URLs and attachments safely
4. Checked Microsoft Defender alerts
5. Quarantine the email if it is malicious
6. Blocked sender/domain
7. Notified affected users
8. Educated the user on phishing indicators

---

## Resolution
Malicious phishing email identified and removed from the user's mailbox. Sender blocked successfully.

---

## Root Cause
Phishing campaign targeting employee credentials.

---

## Tools Used
- Microsoft Defender
- Exchange Admin Center
- Outlook Message Headers
- VirusTotal (safe analysis environment)

---

## Commands / Actions
```powershell
Get-MessageTrace
