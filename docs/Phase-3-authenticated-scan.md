## Phase 3: Authenticated Scan 🔐

This phase dives deeper with credentials, uncovering critical vulnerabilities. 🔍

### Email: Scan Progress 📧
*Context:* You inform Sarah of the authenticated scan’s start.

| Field       | Details                              |
|-------------|--------------------------------------|
| **Subject** | Authenticated Scan in Progress ⏳     |
| **From**    | Adam Cops                        |
| **To**      | Sarah Johnson                      |
| **Date**    | March 10, 2025  📅                   |
| **Body**    | Hi Sarah, I’m running an authenticated scan with the credentials (ADMIN/ADMIN). 🔑 Expect a draft report by March 12. 📝 - Adam |

### Technical Notes ⚙️

Ran `authenticated scan` 🔍: Found 3 high, 3 Medium, and 3 Low confirmed vulnerabilities ⚠️

- Configured Qualys with credentials. 🌐
- Scan results:  
  - Microsoft SMB Server RCE (MS17-010).💥
  - EOL. ⏰
  - Windows SMB Version 1 detected 📡
- Duration: ~30 minutes on 4 GB RAM system. ⏱️

![Scanresult](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/Authenticated%20Scan%20Result.png)
