# Internal Security Audit: Botium Toys

## 1. Project Overview
Botium Toys is a small U.S.-based toy developer and retailer expanding rapidly into global e-commerce. This internal IT audit evaluates their security posture, determines compliance gaps (GDPR, PCI DSS), and aligns their operations with the **NIST Cybersecurity Framework (NIST CSF)**.

## 2. Scope & Goals
* **Scope:** The entire security program at Botium Toys, including employee devices, storefront systems, online servers, and physical assets.
* **Goals:** 
  * Adhere to the NIST CSF guidelines.
  * Establish least privilege access controls.
  * Ensure compliance with international data privacy and payment processing standards (GDPR, PCI DSS).
  * Reduce the overall organizational risk score (initially assessed at 8/10).

## 3. Controls & Compliance Assessment

### Administrative Controls
* **Least Privilege & Separation of Duties:** Flagged for remediation (all staff currently possess wide access).
* **Policies:** Need implementation for disaster recovery, password complexity, and account lifecycles.

### Technical Controls
* **Firewall:** Implemented.
* **IDS / Antivirus:** Needed for real-time anomaly detection and malware quarantine.
* **Data Encryption:** Required for credit card data and customer PII (PCI DSS & GDPR compliance).

### Physical Controls
* **Access Locks & CCTV:** Locking mechanisms required for server/network racks; monitoring required for inventory protection.

## 4. Key Recommendations & Remediation Plan
1. **Implement Role-Based Access Control (RBAC):** Restrict access so employees only access assets necessary for their roles.
2. **Enforce Strong Password Policies & MFA:** Mandate centralized credential management.
3. **Data Protection & Encryption:** Encrypt customer data in transit and at rest to meet GDPR and PCI DSS requirements.
4. **Disaster Recovery Planning:** Implement automated cloud backups and a business continuity playbook.
