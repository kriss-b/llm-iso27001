# Data Classification Policy

## 1. Purpose
This policy establishes a framework for classifying information assets at **ACME CORP** based on their sensitivity and criticality. It ensures that information is handled, protected, and shared in a manner appropriate to its classification level, in alignment with **ISO 27001:2022 (Control A.5.12)**.

---

## 2. Scope
This policy applies to:
- All employees, contractors, and third-party vendors.
- All information assets owned, processed, or stored by the Company, including:
  - Digital data (databases, files, emails, cloud storage).
  - Physical documents (printed reports, contracts, notes).
  - System and application data (logs, configuration files, backups).

---

## 3. Policy Statements

### 3.1 Classification Levels
All information assets must be assigned one of the following classification levels:

| **Level** | **Definition** | **Examples** |
|-----------|---------------|--------------|
| **Public** | Information approved for public disclosure. | Marketing materials, public website content. |
| **Internal** | Information for internal use only; not for public release. | Internal procedures, meeting notes, org charts. |
| **Confidential** | Sensitive information restricted to specific roles or teams. | Customer data, contracts, financial reports, HR records. |
| **Restricted** | Highly sensitive information requiring the strictest controls. | Encryption keys, credentials, audit findings, personal health data. |

### 3.2 Classification Responsibilities
- All information assets must be classified at the time of creation or acquisition.
- Asset owners are responsible for assigning and maintaining the correct classification.
- Classification must be reviewed when assets are transferred, repurposed, or significantly modified.

### 3.3 Labelling
- Digital documents must include the classification level in the file header, metadata, or footer where technically feasible.
- Physical documents must be labelled with the classification level on the first page.

### 3.4 Handling Requirements

| **Level** | **Storage** | **Transmission** | **Disposal** |
|-----------|------------|-----------------|-------------|
| **Public** | No restrictions. | No restrictions. | Standard disposal. |
| **Internal** | Access-controlled systems. | Internal channels only. | Standard disposal. |
| **Confidential** | Encrypted, access-controlled. | Encrypted channels only. | Secure deletion or shredding. |
| **Restricted** | Encrypted, MFA-protected, need-to-know access only. | Encrypted channels, approval required. | Certified destruction. |

### 3.5 Reclassification and Declassification
- Information may be reclassified or declassified when its sensitivity changes (e.g., upon contract expiry or public release).
- Reclassification must be approved by the asset owner and documented.

### 3.6 Third-Party Sharing
- Information shared with third parties must be classified before sharing.
- Third parties must be informed of the classification and required handling obligations.
- Confidential and Restricted information must only be shared under a signed NDA or equivalent contractual protection.

---

## 4. Roles and Responsibilities
### 4.1 CISO (Owner)
- Maintain and enforce this policy.
- Ensure classification standards are communicated to all staff.

### 4.2 Asset Owners
- Assign classification levels to their information assets.
- Review and update classifications as needed.

### 4.3 IT Team
- Implement technical controls to enforce classification-based access restrictions.
- Ensure encryption and access controls align with classification requirements.

### 4.4 Employees
- Apply the correct classification to information they create or handle.
- Report misclassified or improperly handled information to the IT Team.

---

## 5. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts, and legal penalties where applicable.

---

## 6. Review and Updates
This policy will be reviewed **annually** or after significant changes to business processes, data types, or regulatory requirements.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CISO | ISMS Owner | Initial version |
