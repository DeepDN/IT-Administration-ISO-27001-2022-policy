---

# **IT Administration – Information Security Policy**

**Based on ISO/IEC 27001:2022 and Annex A Controls**
**Policy Owner:-** Deepak Nemade.

---

## **1. Asset Management and Protection**

**Annex: 5.9, 5.10, 5.11**

### 1.1 Inventory of IT Assets (Control 5.9)

* Maintain a centralized and up-to-date **IT Asset Register** for all hardware, software, and cloud-based resources.
* Associate each asset with a unique ID, owner, location, and status.
* Conduct physical and logical audits of assets annually.

### 1.2 Acceptable Use of IT Assets (Control 5.10)

* Use organizational assets for authorized business purposes only.
* Prohibited actions include unauthorized installations, accessing offensive content, and storing personal confidential data.
* Internet and endpoint activity may be monitored.

### 1.3 Return of Assets (Control 5.11)

* All assets must be returned during offboarding or role transition.
* The **IT Exit Checklist** must be completed and signed by both IT and the employee.
* Lost or damaged items will be logged and reported to HR.

### Supporting Sub-Policies:

*  [Acceptable Use Policy](./policies/Acceptable_Use_Policy.md)
*  [Information Security Policy](./policies/Information_Security_Policy.md)
*  [Employee Exit Checklist](./checklists/Employee_Exit_Checklist.md)
*  [Asset Disposal Policy](./policies/Asset_Disposal_Policy.md)

(Note: Update links above after placing full documents in repository or system)

* Maintain an updated **inventory of IT assets** including servers, endpoints, network devices, and virtual infrastructure.
* Enforce an **Acceptable Use Policy** for organizational IT assets.
* Ensure **return of assets** upon employee exit, project completion, or when devices are reassigned.

---

## **2. Access Control and Identity Management**

**Annex: 5.15–5.18**

### 2.1 Role-Based Access Control (RBAC) (Control 5.15)

* Apply **Role-Based Access Control** for all systems, applications, and databases.
* Assign access based on the principle of **least privilege**.
* Enforce **segregation of duties** to minimize conflict of interest.

### 2.2 Identity Management (Control 5.16)

* Maintain a centralized **identity management system** to manage user identities across services.
* Ensure that each user has a unique ID and access trail.
* Provisioning and de-provisioning must be formally documented and logged.

### 2.3 Authentication and Password Management (Control 5.17)

* Require use of **strong authentication mechanisms**, including **MFA (Multi-Factor Authentication)**.
* Implement secure **password policies** covering minimum length, expiration, complexity, and reuse.
* Educate users on best practices for handling authentication credentials.

### 2.4 Access Rights Management (Control 5.18)

* Regularly review access permissions **at least quarterly** or upon role change.
* Remove inactive, unnecessary, or excessive rights immediately.
* Maintain an **access review log** signed off by system owners and IT security.

### Supporting Sub-Policies:

*  [Identity and Access Management (IAM) Policy](./policies/Identity_Access_Management_Policy.md)

*  [MFA Enforcement Procedure](./procedures/MFA_Enforcement_Procedure.md)

*  [User Access Review Checklist](./checklists/User_Access_Review_Checklist.md)

* Use **Role-Based Access Control (RBAC)** to restrict access to information systems.

* All accounts must be uniquely identifiable. Implement **strong password policies** and multifactor authentication.

* Regularly **review, modify, or revoke** access rights as per job role changes or employee exit.

* Implement **privileged access management** (PAM) tools and monitor their usage.

---

## **3. Authentication and Secure System Access**

**Annex: 5.17, 8.5**

* Implement centralized **authentication systems** (e.g., LDAP, SSO).
* Enforce **secure password handling practices**, including storage via hashing and encryption.
* Limit authentication retries to reduce brute-force attack risks.

### Supporting Sub-Policies:

####  Acceptable Use Policy

* Use IT assets strictly for authorized business purposes.
* Prohibit unauthorized installations, access to offensive content, and storage of personal confidential data.
* All usage is subject to monitoring and compliance review.

####  Information Security Policy (Summary)

* Ensure confidentiality, integrity, and availability (CIA) of organizational information.
* Enforce risk-based access, secure configurations, patching, backups, and incident response.
* Conduct periodic training and awareness for all staff.

####  Employee Exit Checklist (IT Scope)

| Task                                                | Responsible | Status |
| --------------------------------------------------- | ----------- | ------ |
| Revoke all user accounts and credentials            | IT          | ☐      |
| Recover all IT-issued devices (laptop, phone, etc.) | IT          | ☐      |
| Remove VPN and remote access                        | IT          | ☐      |
| Collect ID card, tokens, keys                       | HR          | ☐      |
| Confirm data backup and secure deletion             | IT          | ☐      |

####  Asset Disposal Policy

* Securely erase or overwrite data before asset disposal.
* Remove all software and license keys.
* Use certified e-waste vendors for recycling or destruction.
* Maintain disposal logs with date, method, and verification.

---

## **4. Network Security and Segregation**

**Annex: 8.20–8.22**

### 4.1 Network Segmentation (Control 8.22)

* Segment networks logically using **VLANs** for users, servers, and guest systems.
* Apply stricter segmentation for sensitive systems such as finance, HR, and production environments.
* Use separate firewalls and routing policies between segmented zones.

### 4.2 Network Protection Mechanisms (Control 8.20)

* Deploy **firewalls**, **IDS/IPS**, and **secure gateways** at all perimeter points.
* Apply **default deny** access control lists.
* Monitor network activity for suspicious patterns in real-time.

### 4.3 Security of Network Services (Control 8.21)

* Maintain an updated **inventory of all network services** (e.g., DNS, VPN, SSH).
* Enforce **encryption for all remote access** (e.g., VPN with MFA).
* Define and maintain **service-level security requirements** for critical systems.

### Supporting Sub-Policies:

*  [Firewall Configuration and Review Policy](./policies/Firewall_Configuration_Review_Policy.md)

*  [Network Segmentation and VLAN Policy](./policies/Network_Segmentation_VLAN_Policy.md)

*  [Remote Access and VPN Usage Policy](./policies/Remote_Access_VPN_Policy.md)

*  [Network Service Inventory and Audit Checklist](./checklists/Network_Service_Audit_Checklist.md)

* All networks must be **segregated by VLANs** for departments, sensitive systems, and guest users.

* Firewalls and intrusion detection/prevention systems (IDS/IPS) must be deployed at all perimeter points.

* Monitor all network devices and maintain **configuration baselines**.

---

## **5. Patch and Vulnerability Management**

**Annex: 8.7, 8.8**

### 5.1 Patch Management (Control 8.7)

* All IT systems must be regularly **patched** for OS, application, and firmware vulnerabilities.
* Patches must be **tested in a staging environment** before deployment to production.
* Define and follow a **patch schedule**, prioritizing critical and high-risk updates.
* Maintain patch logs, approval records, and rollback plans.

### 5.2 Vulnerability Management (Control 8.8)

* Subscribe to trusted **vulnerability feeds** (e.g., NVD, vendor bulletins).
* Perform **monthly internal vulnerability scans** and quarterly external scans.
* Classify and remediate vulnerabilities based on **risk severity and exploitability**.
* Maintain a **vulnerability register** tracking discovery date, risk rating, remediation owner, and status.

### Supporting Sub-Policies:

*  [Patch Deployment Checklist](./checklists/Patch_Deployment_Checklist.md)
*  [Vulnerability Scanning and Reporting Policy](./policies/Vulnerability_Scanning_Reporting_Policy.md)
*  [Remediation SLA Matrix](./checklists/Remediation_SLA_Matrix.md)

---

## **6. Configuration and Change Management**

**Annex: 8.9, 8.32**

### 6.1 Secure Configuration Management (Control 8.9)

* Maintain a centralized repository of **approved baseline configurations** for all hardware, operating systems, software, and network devices.
* Establish version-controlled procedures for any configuration changes.
* Use automated tools to **monitor for deviations** from approved configurations.

### 6.2 Change Management Process (Control 8.32)

* All changes must follow a documented **Change Management Policy**.
* Include risk assessment, impact analysis, rollback procedures, and formal approval.
* Urgent or emergency changes must be logged and reviewed retrospectively.
* Maintain a **Change Log** detailing date, purpose, approver, and results.

### Supporting Sub-Policies:

*  [Secure Configuration Standards Policy](./policies/Secure_Configuration_Standards.md)

*  [Change Management Workflow and Approval Matrix](./checklists/Change_Management_Workflow.md)

*  [Emergency Change Handling Procedure](./procedures/Emergency_Change_Procedure.md)

* Establish and maintain **standard configurations** for servers, endpoints, and network devices.

* All IT-related changes must go through a **Change Management Process** with risk assessment and rollback plans.

---

## **7. Endpoint and Device Security**

**Annex: 8.1, 8.2, 8.3**

### 7.1 Device Management and Control (Control 8.1)

* Deploy **Mobile Device Management (MDM)** solutions to enforce security policies on mobile and remote devices.
* Maintain an inventory of all endpoints issued to users, including location, configuration, and assigned personnel.
* Implement remote wipe capabilities for lost or stolen devices.

### 7.2 Privileged Access Controls (Control 8.2)

* Assign **privileged access** only to authorized personnel and monitor all privileged actions.
* Use **Privileged Access Management (PAM)** tools to enforce just-in-time access where feasible.
* Review privileged access accounts quarterly or upon change of role.

### 7.3 Device Hardening and Access Restriction (Control 8.3)

* Disable unused ports (e.g., USB) and services.
* Apply **device encryption**, password protection, and automatic screen lock.
* Restrict access to sensitive data based on user roles.
* Monitor endpoint compliance using endpoint detection and response (EDR) tools.

### Supporting Sub-Policies:

*  [Endpoint Security Configuration Baseline](./baselines/Endpoint_Security_Configuration.md)
*  [Privileged Access Enforcement Guidelines](./policies/Privileged_Access_Guidelines.md)
*  [Device Hardening Checklist](./checklists/Device_Hardening_Checklist.md) **MDM (Mobile Device Management)** solutions for tracking and enforcing policies on mobile/remote devices.
* Enable **full-disk encryption** for laptops and sensitive endpoint devices.
* Disable unused ports like USB and implement **device control policies**.

---

## **8. Backup and Disaster Recovery**

**Annex: 8.13, 8.14**

### 8.1 Backup Management (Control 8.13)

* Implement **automated backup** solutions for critical data, applications, and configurations.
* Perform **incremental daily** and **full weekly backups**, stored both onsite and offsite/cloud.
* Encrypt backup data at rest and in transit.
* Perform **monthly backup restoration tests** to ensure data integrity and process accuracy.
* Maintain a **backup retention schedule** aligned with legal and business requirements.

### 8.2 Redundancy and Continuity (Control 8.14)

* Implement **redundant hardware**, power supplies, and network connectivity for critical systems.
* Maintain **failover infrastructure** (e.g., secondary data centers, DR-ready cloud environments).
* Document **Recovery Time Objectives (RTO)** and **Recovery Point Objectives (RPO)** for all systems.
* Conduct annual **Disaster Recovery (DR) drills** and update the recovery plan accordingly.

### Supporting Sub-Policies:

*  [Backup Scheduling and Retention Policy](./policies/Backup_Scheduling_Policy.md)

*  [Backup Encryption and Restoration Guidelines](./guidelines/Backup_Encryption_Guidelines.md)

*  [Disaster Recovery Plan and DR Drill Template](./plans/Disaster_Recovery_Plan.md)

* Implement **automated backup** solutions for critical systems and test them monthly.

* Maintain **redundancy** for critical infrastructure (e.g., failover servers, dual ISP).

* Define RTO and RPO aligned with business continuity needs.

---

## **9. Logging, Monitoring, and Incident Response**

**Annex: 8.15–8.17, 5.24–5.27**

### 9.1 Log Management and Analysis (Control 8.15)

* Enable **centralized logging systems** (e.g., SIEM) to collect logs from servers, endpoints, network devices, and applications.
* Protect logs from unauthorized access and tampering.
* Retain logs according to legal or business requirements.
* Review logs regularly to detect anomalies, policy violations, or security events.

### 9.2 Monitoring and Time Synchronization (Controls 8.16–8.17)

* Continuously monitor systems for **unusual activity or threats** using automated tools.
* Define alert thresholds and escalation paths for critical events.
* Synchronize system clocks using **approved NTP sources** to ensure reliable log correlation and forensic readiness.

### 9.3 Incident Response Planning (Control 5.24)

* Develop and maintain an **Incident Response Plan (IRP)** covering preparation, identification, containment, eradication, recovery, and lessons learned.
* Assign roles and responsibilities to the Incident Response Team (IRT).

### 9.4 Incident Identification and Classification (Control 5.25)

* Assess all detected events and determine if they qualify as **security incidents**.
* Classify incidents by type and severity to prioritize handling.

### 9.5 Incident Handling and Response (Control 5.26)

* Document each step of incident handling including affected assets, impact, and response actions.
* Limit impact by isolating systems, revoking access, or deploying patches.
* Notify stakeholders and authorities as required.

### 9.6 Post-Incident Review and Forensics (Controls 5.27–5.28)

* Conduct **post-incident reviews** to identify root causes and recommend corrective actions.
* Establish procedures for **evidence collection** that are forensically sound and legally admissible.

### Supporting Sub-Policies:

*  [Log Retention and Protection Policy](./policies/Log_Retention_Protection_Policy.md)

*  [Security Monitoring and Alerting Procedure](./procedures/Security_Monitoring_Procedure.md)

*  [Incident Response Plan (IRP)](./plans/Incident_Response_Plan.md)

*  [Incident Classification and Reporting Matrix](./checklists/Incident_Classification_Matrix.md)

*  [Digital Forensics and Evidence Handling Guide](./guides/Digital_Forensics_Guide.md)

* Enable **centralized logging** (e.g., SIEM) for system, application, and network events.

* Maintain synchronized **NTP time sources** across systems for accurate log correlation.

* Create an **incident response playbook** with detection, containment, recovery, and post-incident review procedures.

---

## **10. Software and System Development**

**Annex: 8.27–8.30**

### 10.1 Secure System Architecture (Control 8.27)

* Define and maintain **secure architecture principles** for all system and application development.
* Apply **Zero Trust** principles, least privilege, and secure-by-design practices across all development environments.
* Conduct architectural reviews before major implementations.

### 10.2 Secure Coding Standards (Control 8.28)

* Establish and enforce **secure coding practices** aligned with OWASP and other industry standards.
* Provide developer training on secure development techniques.
* Conduct static and dynamic code analysis before releases.

### 10.3 Security Testing and Acceptance (Control 8.29)

* Integrate security testing (e.g., SAST, DAST, penetration tests) into the software development life cycle.
* Document and resolve all critical/high vulnerabilities before deployment.
* Establish criteria for acceptance of secure applications before moving to production.

### 10.4 Outsourced Development Management (Control 8.30)

* Ensure third-party developers follow the same **secure coding and testing** standards as internal teams.
* Include **security and confidentiality clauses** in vendor contracts.
* Perform code reviews and audits for outsourced deliverables.

### Supporting Sub-Policies:

*  [Secure Software Development Life Cycle (SSDLC) Policy](#)

*  [OWASP Secure Coding Guidelines](#)

*  [Vendor Code Review and Contract Checklist](#)

*  [Security Testing and Release Acceptance Policy](#)

* Apply **secure software development lifecycle (SSDLC)** practices.

* Ensure all code is developed using **secure coding guidelines** and tested for vulnerabilities before release.

* Isolate **development, testing, and production** environments strictly.

---

## **11. Cloud Services and Supplier Security**

**Annex: 5.19–5.23**

### 11.1 Supplier Relationship Security (Control 5.19)

* Evaluate and document **security capabilities** of all suppliers and service providers.
* Require suppliers to implement controls appropriate to the sensitivity of the data or service provided.
* Monitor supplier compliance on a regular basis through reports, audits, or reviews.

### 11.2 Supplier Agreements and SLA Management (Control 5.20)

* Ensure all supplier contracts contain **explicit security clauses**, including confidentiality, data protection, and breach notification.
* Define and track **Service Level Agreements (SLAs)** aligned with business and security expectations.
* Include right-to-audit clauses and data ownership provisions in agreements.

### 11.3 ICT Supply Chain Security (Control 5.21)

* Assess and manage security risks within the **ICT supply chain**, including hardware, software, and cloud dependencies.
* Require supply chain participants to follow secure development, delivery, and maintenance practices.

### 11.4 Monitoring and Review of Supplier Services (Control 5.22)

* Conduct periodic reviews of third-party performance, compliance, and risk exposure.
* Maintain a **supplier risk register** and update it based on new threats, incidents, or relationship changes.

### 11.5 Cloud Services Security (Control 5.23)

* Use only **authorized and evaluated cloud services** that meet organizational data protection requirements.
* Review the cloud provider’s certifications (e.g., ISO 27001, SOC 2) and perform periodic risk assessments.
* Ensure access control, encryption, and data segregation are implemented.

### Supporting Sub-Policies:

*  [Third-Party Security Evaluation Checklist](#)

*  [Supplier Contract Security Clause Template](#)

*  [Cloud Services Risk Assessment Policy](#)

*  [Supplier Monitoring and SLA Compliance Policy](#)

* Assess and document **cloud provider compliance** with ISO 27001 and data protection laws.

* Define **security clauses** in all third-party and supplier contracts.

* Monitor **service levels and SLA compliance** regularly.

---

## **12. Physical and Environmental Security**

**Annex: 7.1–7.14**

### 12.1 Security Perimeters and Entry Controls (Controls 7.1–7.2)

* Define **security perimeters** for all critical IT areas including server rooms, communication hubs, and data centers.
* Implement **access control mechanisms** such as RFID cards, biometric scanners, and visitor sign-in logs.
* Review access logs monthly to detect unauthorized access.

### 12.2 Physical Protection of IT Infrastructure (Controls 7.3–7.5)

* Equip rooms with **fire detection and suppression systems**, air conditioning, and water leak sensors.
* Protect against physical threats such as flooding, fire, theft, and vandalism.
* Locate and protect power and communication cables to minimize risks of interception or damage.

### 12.3 Secure Work Areas and Practices (Controls 7.6–7.7)

* Enforce a **Clear Desk and Clear Screen Policy** in all areas handling confidential information.
* Restrict printing and copying of sensitive documents.
* Lock laptops and storage media when unattended.

### 12.4 Equipment Siting, Protection, and Maintenance (Controls 7.8–7.9, 7.13–7.14)

* Place equipment in secured, climate-controlled areas.
* Maintain IT assets according to vendor and organizational schedules.
* For decommissioned equipment, ensure secure disposal or certified erasure.

### 12.5 Off-Premises and Portable Device Controls (Control 7.9)

* Apply protection measures for assets used remotely (e.g., work-from-home laptops).
* Maintain logs for equipment taken outside the premises.
* Mandate encrypted storage for sensitive offsite data.

### 12.6 Storage Media Handling (Control 7.10)

* Define media handling procedures for secure transport, storage, and destruction.
* Use encrypted USBs or secure vaults.
* Keep a log of all storage media issued and returned.

### Supporting Sub-Policies:

*  [Physical Access Control and Visitor Log Policy](#)

*  [Clear Desk & Secure Workspace Guidelines](#)

*  [IT Equipment Disposal and Recycling Policy](#)

*  [Environmental Safety and Emergency Controls Procedure](#)

* Server rooms must have **access control systems** (e.g., biometric, card-based).

* Implement **video surveillance (CCTV)** and intrusion alarms in critical areas.

* Protect cabling and utility infrastructure from unauthorized access or damage.

* Enforce **Clear Desk & Clear Screen Policy** in all workspaces.

---

## **13. Cryptographic Control**

**Annex: 8.24**

### 13.1 Use of Cryptography

* Implement **encryption** for data at rest, in transit, and during processing using approved cryptographic standards such as AES-256 and TLS 1.2+.
* Define requirements for when and how cryptography must be applied (e.g., backups, file sharing, remote access).

### 13.2 Key Management

* Establish a complete **cryptographic key management lifecycle**, including:

  * Key generation and uniqueness
  * Secure key storage and access controls
  * Periodic key rotation and revocation
  * Key disposal procedures upon expiry or retirement

### 13.3 Cryptographic Policy Enforcement

* All cryptographic implementations must be approved by the IT security team.
* Periodically audit cryptographic controls and key management procedures.
* Prohibit usage of outdated or insecure algorithms (e.g., MD5, SHA-1, DES).

### Supporting Sub-Policies:

*  [Cryptographic Usage and Implementation Policy](#)

*  [Key Management Procedure and Schedule](#)

*  [Encryption Standards and Certificate Guidelines](#)

* Use **approved encryption algorithms** (AES-256, TLS 1.2+) for data at rest and in transit.

* Maintain a **key management lifecycle**, including generation, storage, rotation, and disposal.

---

## **14. Software Installation and Utilities Control**

**Annex: 8.18–8.19**

### 14.1 Software Installation (Control 8.19)

* Only authorized IT personnel may install, update, or remove software on organizational systems.
* Maintain an **approved software list** and restrict installations to only listed applications.
* All software must be licensed and sourced from trusted vendors.
* Record software installation and removal logs for audit purposes.

### 14.2 Use of Privileged Utility Programs (Control 8.18)

* Privileged utilities (e.g., disk editors, password recovery tools) must be tightly controlled and monitored.
* Access to utility programs should be granted only on a temporary basis and for legitimate operational purposes.
* Maintain logs of all privileged utility activity and review them regularly.

### Supporting Sub-Policies:

*  [Software Installation and Approval Policy](#)

*  [Privileged Utility Access Request and Review Checklist](#)

*  [Software Asset Inventory Register](#)

* Only IT admins are authorized to **install or remove software** on organizational systems.

* Restrict the use of **privileged utility programs** and monitor their usage.

---

## **15. Web Filtering and Data Leakage Prevention**

**Annex: 8.11, 8.12, 8.23**

### 15.1 Web Filtering Controls (Control 8.11)

* Enforce **enterprise-grade web filtering solutions** (e.g., DNS filtering, proxy-based filters) to block access to malicious, suspicious, or unauthorized websites.
* Regularly update filtering categories and blocklists.
* Monitor and generate reports on web access patterns to detect risky behavior.

### 15.2 Data Loss Prevention (DLP) Measures (Control 8.12)

* Deploy **Data Loss Prevention (DLP)** tools to detect, block, and log unauthorized data transmission via email, USB, web uploads, and cloud sync.
* Classify and tag sensitive data using predefined DLP rules (e.g., personal data, financials, IP).
* Investigate and respond to DLP alerts in coordination with IT Security and HR.

### 15.3 Use of External Services and Shadow IT (Control 8.23)

* Restrict access to **unauthorized external services** (e.g., personal email, unauthorized file-sharing tools).
* Monitor network traffic for **shadow IT** and enforce policies for use of approved services.
* Maintain a list of approved cloud and SaaS applications.

### Supporting Sub-Policies:

*  [Web Filtering Configuration and Exception Policy](#)

*  [DLP Incident Response Guidelines](#)

*  [Shadow IT Detection and Reporting Procedure](#)

* Enforce **web filtering solutions** to block malicious or unauthorized websites.

* Use **Data Loss Prevention (DLP)** tools to monitor sensitive data movement.

---

## **Document Control Reference:**

* **Policy Owner:** Deepak Neamde (IT Department)
* **Last Reviewed:**
* **Next Review:**
* **Version:** 1.0
* **Applicable To:** All IT systems, users, third parties with access to IT resources

---

## **Statement of Applicability (SoA)**

| Control Area                                                    | Applicability | Justification                                                                                        |
| --------------------------------------------------------------- | ------------- | ---------------------------------------------------------------------------------------------------- |
| Asset Management (Annex 5.9–5.11)                               | Applicable    | Controls on asset inventory, usage, and return are critical for IT asset lifecycle management.       |
| Access Control (Annex 5.15–5.18)                                | Applicable    | Ensures proper access is given to users based on roles and responsibilities.                         |
| Authentication & Secure Access (Annex 5.17, 8.5)                | Applicable    | Enforces identity verification and system access security.                                           |
| Network Security (Annex 8.20–8.22)                              | Applicable    | Vital to maintain confidentiality and prevent network-level threats.                                 |
| Patch & Vulnerability Management (Annex 8.7, 8.8)               | Applicable    | Essential for identifying and remediating system weaknesses.                                         |
| Configuration & Change Management (Annex 8.9, 8.32)             | Applicable    | Prevents misconfiguration and ensures controlled implementation of changes.                          |
| Backup & Disaster Recovery (Annex 8.13–8.14)                    | Applicable    | Required to ensure data availability and business continuity.                                        |
| Logging & Incident Response (Annex 5.24–5.27, 8.15–8.17)        | Applicable    | Provides audit trail and coordinated handling of security incidents.                                 |
| Endpoint Security (Annex 8.1–8.3)                               | Applicable    | Prevents unauthorized access or leakage from end-user devices.                                       |
| Cryptography (Annex 8.24)                                       | Applicable    | Ensures confidentiality and integrity of sensitive data.                                             |
| Secure Software Development (Annex 8.27–8.30)                   | Applicable    | Reduces security risks in internally developed applications.                                         |
| Cloud & Supplier Security (Annex 5.19–5.23)                     | Applicable    | Safeguards data handled by third parties and cloud environments.                                     |
| Physical & Environmental Security (Annex 7.1–7.14)              | Applicable    | Protects physical infrastructure and secure areas from unauthorized access or environmental threats. |
| Software Installation & Utilities (Annex 8.18–8.19)             | Applicable    | Controls unauthorized installations and utility tool access.                                         |
| Web Filtering & Data Leakage Prevention (Annex 8.11–8.12, 8.23) | Applicable    | Protects against data exfiltration and unauthorized access to external content.                      |

| Control Area                                             | Applicability | Justification                                                                                  |
| -------------------------------------------------------- | ------------- | ---------------------------------------------------------------------------------------------- |
| Asset Management (Annex 5.9–5.11)                        | Applicable    | Controls on asset inventory, usage, and return are critical for IT asset lifecycle management. |
| Access Control (Annex 5.15–5.18)                         | Applicable    | Ensures proper access is given to users based on roles and responsibilities.                   |
| Network Security (Annex 8.20–8.22)                       | Applicable    | Vital to maintain confidentiality and prevent network-level threats.                           |
| Vulnerability Management (Annex 8.7, 8.8)                | Applicable    | Essential for identifying and remediating system weaknesses.                                   |
| Backup & Disaster Recovery (Annex 8.13–8.14)             | Applicable    | Required to ensure data availability and business continuity.                                  |
| Logging & Incident Response (Annex 5.24–5.27, 8.15–8.17) | Applicable    | Provides audit trail and coordinated handling of security incidents.                           |
| Configuration & Change Management (Annex 8.9, 8.32)      | Applicable    | Prevents misconfiguration and ensures controlled implementation of changes.                    |
| Endpoint Security (Annex 8.1–8.3)                        | Applicable    | Prevents unauthorized access or leakage from end-user devices.                                 |
| Cryptography (Annex 8.24)                                | Applicable    | Ensures confidentiality and integrity of sensitive data.                                       |
| Secure Software Development (Annex 8.27–8.30)            | Applicable    | Reduces security risks in internally developed applications.                                   |
