
---

# **IT Administration – Information Security Policy**

**Based on ISO/IEC 27001:2022 and Annex A Controls**\
**Policy Owner:-** Deepak Nemade.

---

## **1. Asset Management and Protection**

**Annex: 5.9, 5.10, 5.11**

- Maintain an updated **inventory of IT assets** including servers, endpoints, network devices, and virtual infrastructure.
- Enforce an **Acceptable Use Policy** for organizational IT assets.
- Ensure **return of assets** upon employee exit, project completion, or when devices are reassigned.

---

## **2. Access Control and Identity Management**

**Annex: 5.15–5.18**

- Use **Role-Based Access Control (RBAC)** to restrict access to information systems.
- All accounts must be uniquely identifiable. Implement **strong password policies** and multifactor authentication.
- Regularly **review, modify, or revoke** access rights as per job role changes or employee exit.
- Implement **privileged access management** (PAM) tools and monitor their usage.

---

## **3. Authentication and Secure System Access**

**Annex: 5.17, 8.5**

- Implement centralized **authentication systems** (e.g., LDAP, SSO).
- Enforce **secure password handling practices**, including storage via hashing and encryption.
- Limit authentication retries to reduce brute-force attack risks.

---

## **4. Network Security and Segregation**

**Annex: 8.20–8.22**

- All networks must be **segregated by VLANs** for departments, sensitive systems, and guest users.
- Firewalls and intrusion detection/prevention systems (IDS/IPS) must be deployed at all perimeter points.
- Monitor all network devices and maintain **configuration baselines**.

---

## **5. Patch and Vulnerability Management**

**Annex: 8.7, 8.8**

- All IT systems must be regularly **patched** for OS, application, and firmware vulnerabilities.
- Subscribe to trusted sources for **vulnerability intelligence** and assess exposure promptly.
- Maintain a vulnerability management tool (e.g., Trivy, Nessus) with reporting and compliance tracking.

---

## **6. Configuration and Change Management**

**Annex: 8.9, 8.32**

- Establish and maintain **standard configurations** for servers, endpoints, and network devices.
- All IT-related changes must go through a **Change Management Process** with risk assessment and rollback plans.

---

## **7. Endpoint and Device Security**

**Annex: 8.1, 8.2, 8.3**

- Deploy **MDM (Mobile Device Management)** solutions for tracking and enforcing policies on mobile/remote devices.
- Enable **full-disk encryption** for laptops and sensitive endpoint devices.
- Disable unused ports like USB and implement **device control policies**.

---

## **8. Backup and Disaster Recovery**

**Annex: 8.13, 8.14**

- Implement **automated backup** solutions for critical systems and test them monthly.
- Maintain **redundancy** for critical infrastructure (e.g., failover servers, dual ISP).
- Define RTO and RPO aligned with business continuity needs.

---

## **9. Logging, Monitoring, and Incident Response**

**Annex: 8.15–8.17, 5.24–5.27**

- Enable **centralized logging** (e.g., SIEM) for system, application, and network events.
- Maintain synchronized **NTP time sources** across systems for accurate log correlation.
- Create an **incident response playbook** with detection, containment, recovery, and post-incident review procedures.

---

## **10. Software and System Development**

**Annex: 8.27–8.30**

- Apply **secure software development lifecycle (SSDLC)** practices.
- Ensure all code is developed using **secure coding guidelines** and tested for vulnerabilities before release.
- Isolate **development, testing, and production** environments strictly.

---

## **11. Cloud Services and Supplier Security**

**Annex: 5.19–5.23**

- Assess and document **cloud provider compliance** with ISO 27001 and data protection laws.
- Define **security clauses** in all third-party and supplier contracts.
- Monitor **service levels and SLA compliance** regularly.

---

## **12. Physical and Environmental Security**

**Annex: 7.1–7.14**

- Server rooms must have **access control systems** (e.g., biometric, card-based).
- Implement **video surveillance (CCTV)** and intrusion alarms in critical areas.
- Protect cabling and utility infrastructure from unauthorized access or damage.
- Enforce **Clear Desk & Clear Screen Policy** in all workspaces.

---

## **13. Cryptographic Control**

**Annex: 8.24**

- Use **approved encryption algorithms** (AES-256, TLS 1.2+) for data at rest and in transit.
- Maintain a **key management lifecycle**, including generation, storage, rotation, and disposal.

---

## **14. Software Installation and Utilities Control**

**Annex: 8.18–8.19**

- Only IT admins are authorized to **install or remove software** on organizational systems.
- Restrict the use of **privileged utility programs** and monitor their usage.

---

## **15. Web Filtering and Data Leakage Prevention**

**Annex: 8.11, 8.12, 8.23**

- Enforce **web filtering solutions** to block malicious or unauthorized websites.
- Use **Data Loss Prevention (DLP)** tools to monitor sensitive data movement.

---

## **Document Control Reference:**

- **Policy Owner:** Deepak Neamde (IT Department)
- **Last Reviewed:** 
- **Next Review:**
- **Version:** 1.0
- **Applicable To:** All IT systems, users, third parties with access to IT resources

---

## **Statement of Applicability (SoA)**

| Control Area | Applicability | Justification |
|--------------|---------------|----------------|
| Asset Management (Annex 5.9–5.11) | Applicable | Controls on asset inventory, usage, and return are critical for IT asset lifecycle management. |
| Access Control (Annex 5.15–5.18) | Applicable | Ensures proper access is given to users based on roles and responsibilities. |
| Network Security (Annex 8.20–8.22) | Applicable | Vital to maintain confidentiality and prevent network-level threats. |
| Vulnerability Management (Annex 8.7, 8.8) | Applicable | Essential for identifying and remediating system weaknesses. |
| Backup & Disaster Recovery (Annex 8.13–8.14) | Applicable | Required to ensure data availability and business continuity. |
| Logging & Incident Response (Annex 5.24–5.27, 8.15–8.17) | Applicable | Provides audit trail and coordinated handling of security incidents. |
| Configuration & Change Management (Annex 8.9, 8.32) | Applicable | Prevents misconfiguration and ensures controlled implementation of changes. |
| Endpoint Security (Annex 8.1–8.3) | Applicable | Prevents unauthorized access or leakage from end-user devices. |
| Cryptography (Annex 8.24) | Applicable | Ensures confidentiality and integrity of sensitive data. |
| Secure Software Development (Annex 8.27–8.30) | Applicable | Reduces security risks in internally developed applications. |

