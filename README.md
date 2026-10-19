# IT Service Desk Troubleshooting Case Studies

## Overview

This repository documents three hands-on Service Desk troubleshooting cases completed in a simulated IT support environment.

The cases cover common enterprise IT issues involving laptop hardware, corporate wireless connectivity, and Windows file-share authentication.

## Skills Demonstrated

- IT incident analysis and documentation
- Windows workstation troubleshooting
- Hardware and peripheral diagnostics
- Wi-Fi connectivity troubleshooting
- Windows file-share access and authentication
- Saved credential investigation
- Incident resolution documentation

## Case Studies

### 1. Laptop Touchpad Not Working

**Category:** Hardware and Peripherals  
**Priority:** Low  
**Status:** Completed

**Reported issue**

A user reported that the laptop touchpad stopped responding, while an external mouse continued to work.

**Troubleshooting focus**

- Identify whether the issue affects the touchpad only.
- Check touchpad settings and enablement.
- Inspect the device status in Device Manager.
- Investigate potential driver or hardware issues.

**Resolution**

Document the exact corrective action performed and the verification result before publishing this case.

**Key learning:** Isolate the affected component before deciding whether the cause is configuration, driver-related, or hardware-related.

---

### 2. Laptop Unable to Connect to Corporate Wi-Fi

**Category:** Network and Wi-Fi  
**Priority:** Moderate  
**Status:** Completed

**Reported issue**

A user moved to a different office area and reported repeated Wi-Fi connection failures. The user suspected that the laptop was still trying to connect to a previously used wireless network.

**Troubleshooting focus**

- Verify the selected wireless network.
- Check whether the saved network profile matches the intended corporate network.
- Review the connection error and wireless settings.
- Test connectivity after applying the appropriate correction.

**Resolution**

Document the exact network or configuration change performed and confirm the final connection status.

**Key learning:** Changes in a user's work location can expose problems involving saved wireless profiles or network selection.

---

### 3. Windows File Share Rejecting the User's Password

**Category:** Access and File Shares  
**Priority:** Moderate  
**Status:** Completed

**Reported issue**

A user could sign in to Windows and access email after changing an expired password, but the mapped network drive reported an incorrect username or password.

**Investigation**

- Checked the mapped network drives using `net use`.
- Verified the current Windows account using `whoami`.
- Tested direct access to the network share.
- Inspected saved Windows credentials using `cmdkey /list`.
- Identified an outdated saved credential associated with the file server.

**Corrective action**

The troubleshooting process identified the outdated saved credential as the likely cause of the authentication issue. The obsolete credential was targeted for removal.

**Verification**

Record the result of removing the saved credential and remapping the network drive. Confirm that the drive opens successfully before describing the incident as fully resolved.

**Key learning:** Saved credentials can cause authentication failures even when the user's current Windows password is valid.

## Documentation Principles

- Protect user privacy and internal infrastructure details.
- Record observed evidence separately from assumptions.
- Document the actual corrective action and verification result.
- Avoid including passwords, personal information, internal IP addresses, or confidential company data.

## Environment

These case studies were completed in a simulated Service Desk training environment. They demonstrate a structured approach to troubleshooting and incident documentation.

## Disclaimer

This repository is for educational and professional portfolio purposes. It contains sanitized case studies and does not disclose confidential organizational information.
