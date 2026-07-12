# Data Classification Policy

## 1. Purpose
This policy establishes a framework for classifying information assets based on their sensitivity and criticality. It ensures that information is handled, protected, and shared in a manner appropriate to its classification level, in alignment with **ISO 27001:2022 (Control A.5.12)**, using the **Traffic Light Protocol (TLP) 2.0** maintained by FIRST as the labeling scheme.

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
All information assets shall be assigned one of the following classification levels:

| **Level** | **Definition** | **Examples** |
|-----------|---------------|--------------|
| **TLP:CLEAR** | Information approved for unlimited disclosure. | Marketing materials, public website content. |
| **TLP:GREEN** | Information that may be shared within the organization and its trusted peer community, but not via publicly accessible channels. | Internal procedures, meeting notes, org charts. |
| **TLP:AMBER** | Sensitive information limited to the organization and, on a need-to-know basis, its clients. Use **TLP:AMBER+STRICT** to restrict to the organization only, excluding clients. | Customer data, contracts, financial reports, HR records, prompt logs, AI evaluation datasets. |
| **TLP:RED** | Highly sensitive information restricted to named individual recipients only. | Encryption keys, credentials, audit findings, personal health data, proprietary fine-tuned model weights. |

### 3.2 Classification Responsibilities
- All information assets shall be classified at the time of creation or acquisition.
- Asset owners are responsible for assigning and maintaining the correct classification.
- Classification shall be reviewed when assets are transferred, repurposed, or significantly modified.

### 3.3 Labelling
- Labels shall be written in uppercase with the `TLP:` prefix and no space (e.g. `TLP:AMBER`).
- Digital documents shall include the classification level in the file header, metadata, or footer where technically feasible.
- Physical documents shall be labelled with the classification level on the first page.

### 3.4 Handling Requirements

| **Level** | **Storage** | **Transmission** | **Disposal** |
|-----------|------------|-----------------|-------------|
| **TLP:CLEAR** | No restrictions. | No restrictions. | Standard disposal. |
| **TLP:GREEN** | Access-controlled systems. | Internal and trusted-community channels only. | Standard disposal. |
| **TLP:AMBER** | Encrypted, access-controlled. | Encrypted channels, need-to-know. | Secure deletion or shredding. |
| **TLP:RED** | Encrypted, MFA-protected, need-to-know access only. | Encrypted channels, named recipients, approval required. | Certified destruction. |

### 3.5 Reclassification and Declassification
- Information may be reclassified or declassified when its sensitivity changes (e.g., upon contract expiry or public release).
- Reclassification shall be approved by the asset owner and documented.

### 3.6 Third-Party Sharing
- Information shared with third parties shall be classified before sharing.
- Third parties shall be informed of the classification and required handling obligations.
- TLP:AMBER and TLP:RED information shall only be shared under a signed NDA or equivalent contractual protection.

---

## 4. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts, and legal penalties where applicable.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CISO | ISMS Owner | Initial version |
