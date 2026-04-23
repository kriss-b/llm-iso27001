# Cryptography Policy

## 1. Purpose
This policy ensures the secure use of cryptographic controls to protect the confidentiality, integrity, and availability of information in alignment with **ISO 27001:2022 (Control A.8.24 — Use of cryptography)**.

## 2. Scope
This policy applies to all employees, contractors, and third parties who use cryptographic controls to protect the Company’s information assets.

## 3. Policy Statements
### 3.1 Encryption Standards
- **Data at Rest**: Use AES-256 encryption for sensitive data stored on devices or servers.
- **Data in Transit**: Use TLS 1.2 or higher for all data transmissions.
- **Passwords**: Passwords are managed using **Bitwarden (managed service)**, which uses:
  - **End-to-end, zero-knowledge encryption** (AES-CBC 256-bit).
  - **Key Derivation Functions**: PBKDF2 SHA-256 or Argon2id.
  - **HMAC authentication** for data integrity.
  - **FIPS 140-compliant cryptography libraries**.

### 3.2 Key Management
- Encryption keys must be stored securely (e.g., in a key management system like AWS KMS or HashiCorp Vault).
- Keys must be rotated annually or after a suspected compromise.
- Access to keys must be restricted to authorized personnel.

### 3.3 Digital Signatures
- Use digital signatures (e.g., RSA-2048 or ECDSA) to verify the authenticity and integrity of critical documents and transactions.

### 3.4 Prohibited Practices
- Do not use deprecated algorithms (e.g., DES, MD5, SHA-1).
- Do not hardcode encryption keys in source code or configuration files.

## 4. Roles and Responsibilities
### 4.1 CTO (Owner)
- Implement and maintain cryptographic controls.

### 4.2 IT Team
- Support the CTO in implementing cryptographic controls.

### 4.3 Developers
- Ensure cryptographic standards are followed in software development.

### 4.4 Employees
- Comply with encryption requirements for data storage and transmission.

## 5. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

## 6. Review and Updates
This policy will be reviewed annually or after significant changes to cryptographic standards or threats.


---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | ISMS Owner | Initial version |
