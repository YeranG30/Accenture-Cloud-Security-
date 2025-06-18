# Accenture Cloud Security Industry Lab
##  Certificate of Completion  

[Accenture Cloud Security Certificate](https://github.com/YeranG30/Accenture-Cloud-Security-/blob/main/AccentureCloudSecurityCertificate.pdf)

**Issued by Accenture – March 2025**  
Completed via Forage’s Cloud Security Virtual Experience Program

This repository captures my work during Accenture's industry-sponsored Cloud Security Lab. The program simulated real-world security consulting engagements for a healthcare technology firm, with a focus on cloud architecture, scalable IAM, secure SDLC practices, and production-ready incident response.


### **Overview**  
The Accenture Cloud Security Virtual Experience Program provided a realistic simulation of security consulting for Digital Health, a healthcare technology company. Through five intensive tasks, I helped design a secure, scalable cloud infrastructure while balancing compliance and engineering requirements.  Add commentMore actions

**Key Improvements from Original:**  
- Added explicit focus on scalability and incident response  
- Removed redundant resume alignment section  
- Strengthened real-world applicability  

---

### **Task 2 (Enhanced): Security Maturity and IAM Analysis at Scale**  

**Objective:**  
Elevate IAM practices from NIST CSF Tier 1 (Partial) to Tier 2 (Risk-Informed) while ensuring enterprise scalability.  

**Scalability Execution:**  
- Designed **group-based RBAC with attribute-based conditions** to support 10,000+ employees  
- Proposed **AWS Organizations SCPs** to enforce guardrails across multiple business units  
- Architected **just-in-time access workflows** using AWS IAM Identity Center to reduce standing privileges  
- Implemented **automated permission auditing** with AWS Access Analyzer to detect overprivileged roles  

**Incident Response Integration:**  
- Built **IAM breach detection** by:  
  - Configuring CloudTrail logs to feed into SIEM  
  - Creating Lambda functions to alert on suspicious privilege escalation  
  - Developing runbooks for IAM compromise scenarios  
- Established **S3 leak response plan**:  
  - Automated detection via Macie/GuardDuty  
  - Prepared isolation and rotation procedures for exposed credentials  

---

### **Task 3 (Enhanced): SSDLC for 1,000+ Microservices**  

**Scalability Execution:**  
- Designed **security-as-code pipeline** using:  
  - GitHub Actions matrix strategies for parallel security scanning  
  - Policy-as-code with Open Policy Agent (OPA)  
  - Automated exemption management for high-velocity teams  
- Created **service ownership mapping** to:  
  - Automatically route findings to correct teams  
  - Enforce SLAs for vulnerability remediation  
- Implemented **progressive rollout** of security gates:  
  - Phase 1: Critical services only  
  - Phase 2: Tier 1 microservices  
  - Phase 3: Organization-wide enforcement  

**Incident Response Integration:**  
- Established **build-time IR capabilities**:  
  - Automated quarantining of vulnerable artifacts  
  - Breakglass access procedures for emergency fixes  
  - Forensic evidence preservation in CI/CD logs  

---


### **Key Takeaways (Enhanced)**  

1. **Scalable Security Design:**  
   - Proven ability to design controls that work for 10+ employees or 10,000+  
   - Deep understanding of AWS multi-account security  

2. **Production-Grade Incident Readiness:**  
   - Built detection and response into every security layer  
   - Balanced security with operational needs  

3. **Framework Fluency:**  
   - AWS Well-Architected Framework  
   - NIST CSF  
   - MITRE ATT&CK Cloud Matrix  

4. **Toolchain Expertise:**  
   - AWS Native Security (IAM, SCPs, GuardDuty)  
   - CI/CD Security (GitHub Actions, Snyk, OPA)  
   - Infrastructure-as-Code (Terraform)  

---

### **Final Thoughts**  
This experience transformed my approach to cloud security - from theoretical knowledge to operational reality. By focusing on both prevention (through scalable architecture) and response (via embedded detection), I developed solutions that would meet the demands of FAANG-scale environments while remaining practical for real-world deployment.  

The program particularly strengthened my ability to:  
- Translate compliance requirements into automated controls  
- Design security systems that scale exponentially  
- Embed incident response capabilities proactively  

**Tools & Frameworks Mastered:**  
- *Scalability:* AWS Organizations, SCPs, IAM Identity Center  
- *Incident Response:* AWS GuardDuty, Lambda automation  
- *Security-as-Code:* Terraform, OPA, GitHub Actions  
---

### Tools & Frameworks

* AWS: IAM, GuardDuty, Organizations, CloudTrail, S3, Macie
* IaC: Terraform, OPA, GitHub Actions
* Frameworks: NIST CSF, AWS Well-Architected, MITRE ATT&CK Cloud

