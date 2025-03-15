# 🔒 Vulnerability Management Project: SecureSphere Inc. 

Welcome to my vulnerability management project! 🚀 This hands-on assessment simulates a real-world cybersecurity task for a fictional e-commerce company, **SecureSphere Inc.**, using Qualys to scan a Windows 7 VM. It’s designed to help beginners learn the full lifecycle of vulnerability management—from planning to remediation—while showcasing client interactions and technical skills. 📚

## 📖 Project Overview

SecureSphere Inc. is a small online store worried about cyber threats after a competitor’s data breach. They hired **InfoShield** (my fictional consultancy) to assess their Windows 7 VM (IP: 192.168.8.146), which manages orders. I, the fictional character **Adam Cops** (adamcops@infoshield.com), performed unauthenticated and authenticated scans with Qualys, identified critical vulnerabilities (like MS17-010), and provided actionable fixes. This project is documented step-by-step to teach you how to:

- 🗣️ Communicate with clients (emails, meetings).  
- 🔍 Conduct vulnerability scans (basic and authenticated).  
- 📊 Analyze and report findings.  
- 🛠️ Remediate risks and verify fixes.  

## 🛠️ Tools Used

- **Qualys Community Edition** 🌐: For vulnerability scanning.  
- **Windows 7 Ultimate SP1 VM** 💻: Target system (1 GB RAM, VirtualBox).  
- **VirtualBox** 🖥️: Host the VM on my 4 GB RAM system.  

## 📅 Project Phases

This project follows a real-world workflow, split into 6 phases. Each phase includes client communications (emails, meetings) and technical steps, documented for clarity.

| Phase | Description | Link |
|-------|-------------|------|
| 1️⃣ | **Kick-Off** 🎬: Define scope and set expectations with SecureSphere. | [Details](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/docs/Phase-1-kickoff.md) |
| 2️⃣ | **Basic Scan** 🔎: Run an unauthenticated scan to find initial risks. | [Details](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/docs/Phase-2-basic-scan.md) |
| 3️⃣ | **Authenticated Scan** 🔐: Use admin credentials for deeper insights. | [Details](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/docs/Phase-3-authenticated-scan.md) |
| 4️⃣ | **Reporting** 📝: Share findings and remediation plan with the client. | [Details](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/docs/Phase-4-reporting.md) |
| 5️⃣ | **Remediation** 🛡️: Fix vulnerabilities (e.g., patch MS17-010, disable SMBv1). | [Details](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/docs/Phase-5-remediation.md) |
| 6️⃣ | **Debrief** ✅: Deliver the final report and reflect on lessons learned. | [Details](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/docs/Phase-6-debrief.md) |

## 📄 Reports

Check out the `Report and Snippets` for a reference:

- [Unauthenticated Scan Results](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/basic-scan-result.png) 📷  
- [Authenticated Scan Results](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/authenticated-scan-result.png) 📷  
- [Assessment Report](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/Network-Vulnerability-Assessment-Report-SecureSphere.pdf) 📔

## 📜 Final Report

The full vulnerability report for SecureSphere Inc. is available here: [Final Report](https://github.com/mohamedshibil/SecureSphere-Assessment/blob/main/docs/final-vulnerability-assessment-report-SecureSphere.pdf) 📄. It includes:

- **Executive Summary** 📋: High-level overview for non-technical readers.  
- **Vulnerability Details** ⚠️: Names, CVSS scores, severity, and fixes (e.g., MS17-010, CVSS 9.3, Critical).  
- **Remediation Steps** 🔧: Clear actions to secure the system.  

## 🌟 Key Takeaways (For Beginners)

- **Client Communication** 💬: Learn how to scope projects, request credentials, and present findings professionally.  
- **Scan Types** 🔍: Unauthenticated scans catch surface issues; authenticated scans reveal deeper risks (e.g., 2x more vulnerabilities found).  
- **Prioritization** 📊: Use CVSS scores to focus on critical issues first (e.g., MS17-010 over NetBIOS).  
- **Resource Management** ⚙️: Carefully allocate lightweight VMs on a 4 GB RAM system.  

**Pro Tip** 💡: Always explain technical terms to clients in simple language—e.g., “This flaw lets hackers take over your computer” instead of “Remote Code Execution.”

## 🚀 How to Get Started

Want to try this yourself? Here’s how to set it up:

1. **Install VirtualBox** 🖥️: Free virtualization software ([Download](https://www.virtualbox.org/)).  
2. **Set Up a Windows 7 VM** 💻: Use a legal ISO, allocate 1 GB RAM, and assign an IP (e.g., 192.168.8.146).  
3. **Get Qualys** 🌐: Sign up for the Community Edition or trial ([Qualys Free Trial](https://www.qualys.com/free-trial/)).  
4. **Follow the Phases** 📅: Use my docs to guide your assessment.

## 🤝 Contributing

This project is a learning resource, so contributions are welcome! If you have suggestions, please feel free to open an issue or submit a pull request. Let’s learn together! 🌱

## 📧 Contact

I’m **Mohamed Shibil**. Reach out for questions or feedback:  
📧 hello@beyondshibil.com  
🌐 Beyondshibil.com 

## ⭐ Let’s Connect!

If you found this project helpful, give it a star on GitHub! ⭐ It motivates me to share more cybersecurity projects. 😊
