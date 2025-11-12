# 🧪 Cybersecurity Lab Report ![Lab Report](https://img.shields.io/badge/Status-Completed-brightgreen) ![Framework](https://img.shields.io/badge/Framework-NIST%20%7C%20MITRE%20ATT&CK-blue) ![Tools](https://img.shields.io/badge/Tools-SIEM%2C%20Sysmon%2C%20TheHive-orange)

---

## **1. Lab Title**
> Incident Handling Simulation: Nexus Data Breach Response

---

## **2. Purpose and Objectives**

The objective of this lab is to simulate a real-world cybersecurity incident and apply structured methodologies to detect, analyze, contain, and remediate threats.

**Key Learning Outcomes:**
- Apply the incident response lifecycle (NIST SP 800-61) in a SOC environment.
- Conduct threat hunting, SIEM log analysis, and incident triage.
- Investigate credential compromises and web application vulnerabilities.
- Perform forensic analysis and remediate malicious artifacts.
- Map attacker behaviors to MITRE ATT&CK techniques.

---

## **3. Frameworks, Standards, and Methodologies**
- **NIST SP 800-61:** Computer Security Incident Handling Guide  
- **MITRE ATT&CK:** Tactics and Techniques Mapping  
- **Defense-in-Depth & RBAC Principles**  
- **Post-Incident Forensics & Digital Forensics Methodologies**

---

## **4. Tools and Technologies**
- **SIEM:** Wazuh  
- **Endpoint Monitoring:** Sysmon  
- **Incident Management:** TheHive  
- **Threat Intelligence & Analysis:** CyberChef, VirusTotal  
- **System Environment:** Windows Server 2022, Active Directory  
- **Utilities:** PowerShell, MD5/Encoding Analysis, Log Correlation  

---

## **5. Procedures and Implementation**
<details>
<summary>Click to expand detailed steps</summary>

1. Collected Windows event logs via Sysmon integrated with Wazuh SIEM.  
2. Conducted threat hunting and incident triage to verify IoCs, including suspicious IPs, file hashes, and network anomalies.  
3. Investigated **ManageEngine credential compromise** and **PHP portal vulnerabilities**, identifying lateral movement, privilege escalation, and GPO-deployed malware.  
4. Extracted and decoded threat actor IPs using CyberChef; verified IP locations via VirusTotal.  
5. Performed post-incident forensic analysis including memory dumps, disk images, and log correlation.  
6. Removed malicious artifacts, restored clean system states, and validated configuration integrity.  
7. Mapped findings to MITRE ATT&CK TTPs and ensured alignment with NIST SP 800-61 incident handling lifecycle.

</details>

---

## **6. Findings and Results**
- Detected multiple Indicators of Compromise (IoCs) across endpoints and network logs.  
- Uncovered credential compromise and unauthorized privilege escalations.  
- Identified GPO-deployed malware and lateral movement in the domain.  
- Successfully remediated malicious artifacts and restored system integrity.  
- Verified threat actor IPs and decoded artifacts for full investigative context.

---

## **7. Analysis and Interpretation**

SIEM alerts and threat hunting workflows highlighted the importance of **proactive monitoring** in incident response.  
MITRE ATT&CK mapping contextualized attacker behaviors, while forensic investigations and remediation reinforced the value of **structured and compliant incident handling**.

---

## **8. Technical Skills and Competencies Demonstrated**
- Threat hunting and SOC alert triage  
- SIEM log correlation and IoC verification  
- Forensic analysis of memory dumps, disk images, and logs  
- Vulnerability remediation and system hardening  
- Incident response workflow aligned with NIST SP 800-61 and MITRE ATT&CK

---

## **9. Lessons Learned**

- Structured monitoring and compliance-aligned controls are essential for SOC effectiveness.  
- Effective log analysis and threat hunting enhance organizational cybersecurity posture.  
- Integrating forensic investigations with incident response improves detection and recovery capabilities.

---

## **10. Conclusion**

This lab demonstrated applied expertise in **incident response, SIEM operations, threat hunting, and forensic analysis**, aligned with industry frameworks.  
Integrating technical controls with structured methodologies reinforced **proactive and professional information security management**.

---

## **11. References**
- National Institute of Standards and Technology. *NIST SP 800-61 Rev. 2: Computer Security Incident Handling Guide.* 2012.  
- MITRE ATT&CK Framework. *Tactics, Techniques, and Procedures (TTPs).* 2025.  
- Hack The Box Academy. *Incident Handling Process Module.* 2025.
