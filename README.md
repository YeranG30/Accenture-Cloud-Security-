# Accenture Cloud Security Industry Lab
##  Certificate of Completion  

[Accenture Cloud Security Certificate](https://github.com/YeranG30/Accenture-Cloud-Security-/blob/main/AccentureCloudSecurityCertificate.pdf)

**Issued by Accenture – March 2025**  
Completed via Forage’s Cloud Security Virtual Experience Program

This repository captures my work during Accenture's industry-sponsored Cloud Security Lab. The program simulated real-world security consulting engagements for a healthcare technology firm, with a focus on cloud architecture, scalable IAM, secure SDLC practices, and production-ready incident response.

---

###  Overview

As a Cloud Security Industry Lab Participant, I completed five hands-on tasks simulating real-world client scenarios. Key themes included:

* Scalable Identity & Access Management (IAM)
* Secure Software Development Lifecycle (SSDLC)
* Cloud-native incident response
* Security architecture patterns for multi-account AWS environments

---

###  Task 2: Security Maturity & IAM at Scale

**Objective:**  
Elevate IAM practices from NIST CSF Tier 1 (Partial) to Tier 2 (Risk-Informed) with scalable enterprise security.

**Key Deliverables:**
* Designed **group-based RBAC** with **attribute-based conditions** to manage 10,000+ users
* Proposed **AWS Organizations SCPs** to enforce guardrails across accounts
* Architected **just-in-time access** via AWS IAM Identity Center
* Implemented **automated access reviews** using AWS Access Analyzer

**Incident Response Enhancements:**
* Built detection logic for IAM privilege escalation via:
  * **CloudTrail → Lambda → SIEM alert pipeline**
  * Runbooks for IAM key compromise and role abuse
* Designed a response playbook for **S3 data leak scenarios** using:
  * Macie, GuardDuty, IAM rotation plans

---

###  Task 3: SSDLC for 1,000+ Microservices

**Objective:**  
Secure high-velocity development pipelines with enforceable security guardrails.

**Security-as-Code Implementation:**
* Integrated security gates using:
  * **GitHub Actions matrix builds**
  * **Open Policy Agent (OPA)** for policy-as-code enforcement
* Developed **automated SLA routing** for vulnerability ownership
* Rolled out controls in **3 progressive phases**:
  1. Critical systems
  2. Tier 1 microservices
  3. Org-wide enforcement

**Build-Time Incident Response:**
* Quarantined vulnerable builds with automated rollback
* Enabled **breakglass access** for emergency deploys
* Preserved forensic data via CI/CD artifact logging

---

###  Cross-Task Scalability Patterns

**Centralized Security Telemetry:**
* Built a **unified security data lake** aggregating:
  * CloudTrail logs
  * Snyk scan results
  * AWS Security Hub posture data
* Developed **correlation rules** to detect chained threats:
  * IAM key misuse followed by privilege changes
  * Vulnerability spikes during deploys

**Planet-Scale Automation:**
* Wrote **Terraform modules** for:
  * Guardrail SCPs
  * IAM analyzer deployment
  * Misconfiguration auto-remediation
* Created a **self-service portal** to:
  * Request temporary elevation
  * Check team compliance
  * Launch role-based security training

---

###  Key Skills Demonstrated

* Cloud IAM Architecture (AWS IAM, SCPs, Identity Center)
* Secure SDLC Pipeline Automation (GitHub Actions, OPA)
* Cloud-native Incident Response (GuardDuty, Lambda, Macie)
* Infrastructure as Code (Terraform Modules)
* Multi-account Security Engineering (AWS Organizations)
* Compliance Automation (NIST CSF, AWS Well-Architected)

---

### Final Takeaways

This lab transformed theoretical knowledge into operational, real-world cloud security implementation. I learned to:

* Design scalable controls for orgs of any size (10 → 10,000)
* Translate compliance frameworks into automated guardrails
* Build proactive detection and response workflows into infrastructure

---

### Tools & Frameworks

* AWS: IAM, GuardDuty, Organizations, CloudTrail, S3, Macie
* IaC: Terraform, OPA, GitHub Actions
* Frameworks: NIST CSF, AWS Well-Architected, MITRE ATT&CK Cloud

