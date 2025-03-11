## Phase 2: Basic Scan

This phase shares initial unauthenticated scan results and requests credentials for deeper analysis.
<br>
### Email: Basic Scan Results
*Context:* You update Sarah after running the first scan.

| Field       | Details                              |
|-------------|--------------------------------------|
| **Subject** | Basic Scan Results  |
| **From**    | Adam Cops (adamcops@infoshield.com) |
| **To**      | Sarah Johnson (sarah.johnson@securesphere.com) |
| **Date**    | March 9, 2025                       |
| **Body**    | Hi Sarah, I scanned your Windows 7 VM (192.168.8.146) with Qualys. Found interesting vulnerabilities, missing patches, outdated software, etc. Can you share admin credentials for an authenticated scan? Update by March 11. - Adam |
---
### Email: Sarah’s Response
*Context:* Sarah provides credentials.

| Field       | Details                              |
|-------------|--------------------------------------|
| **Subject** | Re: Basic Scan Results |
| **From**    | Sarah Johnson |
| **To**      | Adam Cops |
| **Date**    | March 9, 2025                       |
| **Body**    | Hi Adam, Thanks for the update. Credentials: `Username`: "ADMIN", `Password`: "ADMIN". Let me know how it goes! - Sarah |

---
> [!IMPORTANT]
> Sharing **credentials** securely is a real-world challenge—here, it’s simulated via email for simplicity.

### Technical Notes
- Ran `unauthenticated scan`: Found 3 high vulns (e.g., RCE, EOL).  
![Screenshot](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/basic%20scan%20result.png)
