# Access Control Policy

## 1. **Purpose**
This **Access Control Policy** defines the requirements for managing access to **ACME CORP**'s information assets. It ensures that access is **granted, modified, and revoked** in accordance with the **principle of least privilege**, in alignment with **ISO 27001:2022 (Controls A.5.15 – A.5.18, A.8.2 – A.8.5)**, which cover identity management, authentication, access rights, and privileged access.

---

## 2. **Scope**
This policy applies to:
- All employees, contractors, and third-party vendors.
- All information assets, including:
  - Systems (cloud services, internal networks, endpoints).
  - Data (customer data, company data, intellectual property).
  - Physical assets (servers, workstations, mobile devices).

---

## 3. **Policy Statements**

### 3.1 **Access Control Principles**
- Access to information assets must be **granted based on business need** and **least privilege**.
- Access rights must be **reviewed quarterly** and revoked when no longer needed.
- **Multi-Factor Authentication (MFA)** is required for:
  - Remote access to company systems.
  - Privileged accounts (e.g., admin, root).
  - Access to customer data.

### 3.2 **User Access Management**
- **User Registration**: All users must be **formally registered** before access is granted. Registration must include:
  - Approval from the user’s manager.
  - Unique user ID (no shared accounts).
  - Assignment of appropriate roles/permissions.
- **User De-Registration**: Access must be **revoked immediately** upon termination or role change.
- **Privileged Access**: Privileged accounts must be:
  - Approved by the **CTO**.
  - Monitored and logged.
  - Reviewed **quarterly**.

### 3.3 **Authentication**
- **Passwords**:
  - Minimum length: **12 characters**.
  - Complexity: **Uppercase, lowercase, numbers, and special characters**.
  - Passwords must be **changed every 90 days**.
  - Passwords must **not be reused** for at least 5 cycles.
  - Passwords must **not be shared** or written down.
- **MFA**:
  - MFA must be enabled for all remote access and privileged accounts.
  - MFA methods: **TOTP (Time-Based One-Time Password)** or **hardware tokens**.

### 3.4 **Access Review**
- Access rights must be **reviewed quarterly** by asset owners.
- Reviews must be **documented** and retained for **1 year**.
- Unnecessary or excessive access must be **revoked immediately**.

### 3.5 **Third-Party Access**
- Third-party access must be **approved by the CTO** and **documented in contracts**.
- Third parties must comply with this policy and the **[Supplier Security Policy](supplier_security_policy.md)**.
- Access must be **revoked immediately** upon contract termination.

### 3.6 **Remote Access**
- Remote access must be **secured using MFA** and **encrypted connections (VPN or SSH)**.
- Remote sessions must be **logged and monitored**.

### 3.7 **Physical Access**
- Physical access to servers and workstations must be **restricted to authorized personnel**.
- Access to data centers must be **logged and reviewed quarterly**.

---

## 4. **Roles and Responsibilities**
| **Role**                     | **Responsibility**                                                                 |
|-----------------------------|-----------------------------------------------------------------------------------|
| **CEO**                     | Ultimate responsibility for access control.                                      |
| **CTO**                     | Approve privileged access and enforce access control policies.                   |
| **Managers**                | Approve access requests for their teams and conduct access reviews.              |
| **Employees**               | Comply with access control policies and report suspicious activity.               |
| **Third-Party Vendors**     | Comply with access control requirements and contractual obligations.              |

---

## 5. **Compliance**
- Non-compliance with this policy may result in **disciplinary action**, up to and including termination.
- Access rights may be **revoked** for non-compliance.

---

## 6. **Review and Update**
- This policy must be **reviewed annually** or after significant changes.
- Updates must be **approved by the CEO** and communicated to all stakeholders.

---

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | ISMS Owner | Initial version |
