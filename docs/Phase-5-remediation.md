
## Phase 5: Remediation 🛠️

This phase fixes vulnerabilities and prepares for verification. ✅

### Email: Remediation Update 📧

| Field       | Details                              |
|-------------|--------------------------------------|
| **Subject** | Remediation Underway 🔧  |
| **From**    | Adam Cops (Adamcops@infoShield.com) |
| **To**      | Sarah Johnson (sarah.johnson@securesphere.com) |
| **Date**    | March 13, 2025 📅                      |
| **Body**    | Hi Sarah, I’m patching MS17-010 💥 and disabling SMBv1 📡 on the VM. I will rescan to confirm the fixes. 🔍 The final report will be soon! 📝 - Adam Cops |


### Technical Notes ⚙️

- Applied patches via Windows Update (e.g., KB4012212). 🖥️
- Disabled SMBv1: `Set-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Services\LanmanServer\Parameters" SMB1 -Type DWORD -Value 0`. 🔒
