# Ticket 11 - Application Installation Failure

## Ticket Information
- **Ticket ID:** APP-011
- **Priority:** Medium
- **Category:** Software Installation
- **Status:** Resolved
- **Reported By:** [Username]
- **Assigned To:** [Your Name]
- **Date Opened:** [Date]
- **Date Resolved:** [Date]

---

## User Issue
User is unable to install the approved company application on the workstation.

---

## Environment
- Windows 10/11
- Domain-Joined Workstation
- Software Deployment Environment
- Local Administrator Permissions Required

---

## Symptoms
- Installation wizard fails
- “Access Denied” message
- Installer freezes or crashes
- Missing dependencies
- Installation rollback occurs

---

## Troubleshooting Steps
1. Verified installer integrity
2. Confirmed local administrator permissions
3. Checked available disk space
4. Reviewed installation logs
5. Disable antivirus temporarily if needed
6. Installed required dependencies
7. Ran the installer as an administrator
8. Restarted workstation after install

---

## Resolution
Application installed successfully after correcting permissions/dependencies.

---

## Root Cause
Insufficient permissions or missing system requirements prevented installation.

---

## Commands / Tools Used
```powershell
msiexec /i application.msi
