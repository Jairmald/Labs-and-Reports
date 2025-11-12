# 🔐 Implementing a Risk Mitigation Framework — Hands-On Lab Experience

**Author:** Jair Maldonado  
**Course:** *Managing Risk in Information Systems (3e) — Lab 08*  
**Focus:** ISO/IEC 27002 Compliance • Windows Security Hardening • Enterprise Risk Mitigation  
**Completion Date:** November 2, 2025  

---

## 🧭 Overview
This hands-on lab focused on implementing a **Risk Mitigation Framework** through applied **information security controls** and **Windows system hardening**.  
Key objectives included enforcing security policies, configuring Active Directory, managing access control, and aligning technical configurations with **ISO/IEC 27002** standards.

---

## ⚙️ Systems & Infrastructure

| System | Description | Key Actions |
|---------|--------------|--------------|
| **Windows Server** | Domain Controller | Configured **Active Directory**, implemented **password policies**, and enforced **RBAC**. |
| **TargetWindows01** | Endpoint Target | Performed **system hardening**, disabled **Microsoft FTP service**, and removed **unpatched third-party tools**. |
| **vWorkstation** | Workstation Client | Validated **authentication**, **user access**, and **policy propagation**. |
| **Windows Domain Controller** | Policy Enforcement Node | Centralized **RBAC**, **audit logging**, and **policy management**. |

---

## 🔑 Security Policy & Password Management

- Revised the **Information Security Policy** to include:
  - Minimum **16-character** passwords
  - **Uppercase, lowercase, numeric, and special** character requirements  
  - **Randomness and uniqueness** enforced across accounts
- Applied **domain-wide enforcement** via Active Directory Group Policy.  
- Validated **RBAC roles**, **credential management**, and **policy inheritance**.  

---

## 🧱 System Hardening & Data Sanitization

### TargetWindows01
- Enabled **Windows Update** for automated patching.  
- Disabled unnecessary services (e.g., **Microsoft FTP**) to reduce the attack surface.  
- Removed outdated or **unpatched third-party management tools**.  
- Executed **data sanitization** across:
  - *Documents directory*  
  - *FTP root*  
  - *Recycle Bin*

---

## 🗂️ Active Directory Management
- Removed **unauthorized domain accounts**.  
- Enforced **group policy** configurations across all systems.  
- Validated **access control isolation** and user permissions.

---

## 🧩 ISO/IEC 27002 Controls Implemented

| Control Area | Implementation Summary |
|---------------|------------------------|
| **Data Protection** | Applied encryption standards and access restrictions for sensitive information. |
| **Information Security Policy** | Updated policies to prohibit plaintext storage and unapproved cloud service usage. |
| **Security Awareness & Training** | Instituted compliance acknowledgment and user training requirements. |
| **Vulnerability Management** | Conducted vulnerability scans, applied patches, and validated system compliance. |

---

## 🛡️ Additional Security Measures

- **Data Loss Prevention (DLP):** Configured automated data leakage policies.  
- **Threat Intelligence & SIEM:** Centralized log aggregation and real-time alerting.  
- **Secure Disposal:** Implemented **cryptographic wiping** for decommissioned assets.  
- **Configuration Management:** Established **baseline security standards** across all systems.  

---

## 🧠 Key Technical Skills Demonstrated
- Windows Server Administration & Domain Security  
- Active Directory Policy Enforcement (RBAC, GPO)  
- System Hardening & Vulnerability Remediation  
- Data Protection & Encryption Controls  
- SIEM Integration & Threat Monitoring  
- ISO/IEC 27002 Control Implementation  

---

## 📈 Outcome
This lab reinforced practical knowledge of **enterprise risk mitigation**, **policy-driven security**, and **technical compliance**.  
The result: a hardened Windows environment aligned with **ISO/IEC 27002** principles and improved overall **organizational security posture**.

---

### 🏷️ Tags
`#Cybersecurity` `#InfoSec` `#WindowsServer` `#ActiveDirectory` `#RiskManagement`  
`#ISO27002` `#SystemHardening` `#DataProtection` `#SecurityCompliance`

---

> **“Security is not a product — it’s a process.”**  
> — Bruce Schneier
