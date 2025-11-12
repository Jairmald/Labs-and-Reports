# 🧪 Cybersecurity Lab Report

![Lab Report](https://img.shields.io/badge/Status-Completed-brightgreen)
![Framework](https://img.shields.io/badge/Framework-NIST%20%7C%20ISO%2FIEC%2027002-blue)
![Tools](https://img.shields.io/badge/Tools-SIEM%2C%20Sysmon%2C%20TheHive-orange)

---

## **1. Lab Title**
> Example: Incident Handling Simulation: Nexus Data Breach Response

---

## **2. Purpose and Objectives**
The objective of this lab is to simulate a real-world cybersecurity scenario and apply structured methodologies to detect, analyze, contain, and remediate threats.  

**Key Learning Outcomes:**
- Apply incident response lifecycle (NIST SP 800-61).  
- Conduct log analysis and alert triage.  
- Implement security controls aligned with ISO/IEC 27002.

---

## **3. Frameworks, Standards, and Methodologies**
- **NIST SP 800-61:** Computer Security Incident Handling Guide  
- **ISO/IEC 27002:** Information Security Controls and Compliance  
- **MITRE ATT&CK:** Tactics and Techniques Mapping  
- **Defense-in-Depth & RBAC Principles**

---

## **4. Tools and Technologies**
- **SIEM:** Wazuh, Elastic Stack (Kibana, Elasticsearch)  
- **Endpoint Monitoring:** Sysmon  
- **Incident Management:** TheHive  
- **System Environment:** Windows Server 2022, Active Directory  
- **Security Controls:** GPO, RBAC, DLP  
- **Utilities:** PowerShell, Nmap, Nessus, CVE scanners

---

## **5. Procedures and Implementation**
<details>
<summary>Click to expand detailed steps</summary>

1. Collected Windows event logs via Sysmon integrated with Wazuh SIEM.  
2. Developed KQL queries to detect failed logons, RDP brute-force attempts, and privilege escalation.  
3. Mapped detection results to MITRE ATT&CK TTPs.  
4. Applied ISO/IEC 27002 controls for password, access, and audit policy enforcement.  
5. Verified remediation with vulnerability scans and compliance checks.

</details>

---

## **6. Findings and Results**
- Multiple anomalous logon attempts detected.  
- Unauthorized administrative group changes identified and remediated.  
- Critical vulnerabilities reduced from 5 to 0 post-hardening.  
- SIEM visualizations validated compliance and improved detection coverage.

---

## **7. Analysis and Interpretation**
The SIEM alerts highlighted the value of proactive monitoring within incident response. MITRE ATT&CK mapping provided context to attacker techniques, while ISO/IEC 27002 controls ensured systematic enforcement of security policies.

---

## **8. Technical Skills and Competencies Demonstrated**
- SOC alert triage and SIEM log correlation  
- Threat detection and KQL query building  
- Vulnerability remediation and system hardening  
- RBAC configuration and compliance enforcement  
- Incident response and forensic investigation techniques

---

## **9. Lessons Learned**
This lab emphasized the importance of structured monitoring and compliance-aligned controls. Effective log analysis and remediation enhance both technical and organizational cybersecurity posture.

---

## **10. Conclusion**
The lab demonstrated applied expertise in SIEM operations, incident response, and compliance alignment. Integration of technical controls with established frameworks reinforced the importance of proactive and structured information security management.

---

## **11. References**
- National Institute of Standards and Technology. *NIST SP 800-61 Rev. 2: Computer Security Incident Handling Guide.* 2012.  
- International Organization for Standardization. *ISO/IEC 27002: Information Security, Cybersecurity, and Privacy Protection.* 2022.  
- MITRE ATT&CK Framework. *Tactics, Techniques, and Procedures (TTPs).* 2025.

---
