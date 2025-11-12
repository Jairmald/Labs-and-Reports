# 🧪 Implementing a Risk Mitigation Framework

![Lab Report](https://img.shields.io/badge/Status-Completed-brightgreen)
![Framework](https://img.shields.io/badge/Framework-ISO%2FIEC%2027002-blue)
![Tools](https://img.shields.io/badge/Tools-Active%20Directory%20%26%20GPO-orange)
![Difficulty](https://img.shields.io/badge/Difficulty-Intermediate-yellow)
![Completion](https://img.shields.io/badge/Completion-November%202%2C%202025-lightblue)

---

## **1. Lab Title**

> Implementing a Risk Mitigation Framework: ISO/IEC 27002 Compliance & Windows Security Hardening

---

## **2. Purpose and Objectives**

Implement a **Risk Mitigation Framework** through applied **information security controls** and **Windows system hardening** aligned with **ISO/IEC 27002** standards.

---

## **3. Systems & Infrastructure**

| System | Role | Key Actions |
|--------|------|------------|
| **Windows Server** | Domain Controller | Active Directory, password policies, RBAC |
| **TargetWindows01** | Endpoint Target | System hardening, service disabling, data sanitization |
| **vWorkstation** | Workstation Client | Authentication validation, policy propagation testing |

---

## **4. Security Policy & Password Management**

**Information Security Policy Updates:**
- Minimum **16-character** passwords
- **Uppercase, lowercase, numeric, and special** character requirements
- Randomness and uniqueness enforced across accounts
- Applied **domain-wide enforcement** via Active Directory Group Policy

---

## **5. System Hardening & Data Sanitization**

**TargetWindows01 Actions:**
- Enabled **Windows Update** for automated patching
- Disabled unnecessary services: **Microsoft FTP** (ports 21-22)
- Removed **unpatched third-party management tools**
- Executed data sanitization:
  - Documents directory
  - FTP root directory
  - Recycle Bin

---

## **6. Active Directory Management**

- Removed **unauthorized domain accounts**
- Enforced **group policy** configurations across all systems
- Validated **access control isolation** and user permissions

---

## **7. ISO/IEC 27002 Controls Implemented**

| Control Area | Implementation |
|--------------|-----------------|
| **Data Protection** | Encryption standards & access restrictions for sensitive information |
| **Information Security Policy** | Updated policies prohibiting plaintext storage & unapproved cloud services |
| **Security Awareness & Training** | Compliance acknowledgment & user training requirements |
| **Vulnerability Management** | Vulnerability scans, patch application, system compliance validation |

---

## **8. Additional Security Measures**

- **Data Loss Prevention (DLP):** Automated data leakage prevention policies
- **Threat Intelligence & SIEM:** Centralized log aggregation & real-time alerting
- **Secure Disposal:** Cryptographic wiping for decommissioned assets
- **Configuration Management:** Baseline security standards across all systems

---

## **9. Key Technical Skills Demonstrated**

- Windows Server Administration & Domain Security
- Active Directory Policy Enforcement (RBAC, GPO)
- System Hardening & Vulnerability Remediation
- Data Protection & Encryption Controls
- SIEM Integration & Threat Monitoring
- ISO/IEC 27002 Control Implementation

---

## **10. Outcome**

Hardened Windows environment **aligned with ISO/IEC 27002** principles with improved overall **organizational security posture** through policy-driven security and technical compliance enforcement.

---

## **References**

- [ISO/IEC 27002:2022 - Information Security Controls](https://www.iso.org/standard/75652.html)
- [Microsoft Active Directory Security Best Practices](https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/best-practices-for-securing-active-directory)
- [Windows Group Policy Overview - Microsoft](https://docs.microsoft.com/en-us/windows/win32/adsi/group-policy)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

---

**Course:** Managing Risk in Information Systems (3e) — Lab 08  
**Author:** Jair Maldonado  
**Completion Date:** November 2, 2025
