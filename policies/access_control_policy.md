# Access Control Policy

## 1. **Purpose**
This **Access Control Policy** defines the requirements for managing access to the organization's information assets. It ensures that access is **granted, modified, and revoked** in accordance with the **principle of least privilege**, in alignment with **ISO 27001:2022 (Controls A.5.15 – A.5.18, A.8.2 – A.8.5)**, which cover identity management, authentication, access rights, and privileged access.

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
- Access to information assets shall be **granted based on business need** and **least privilege**.
- Access rights shall be **reviewed quarterly** and revoked when no longer needed.
- **Multi-Factor Authentication (MFA)** is required for:
  - Remote access to company systems.
  - Privileged accounts (e.g., admin, root).
  - Access to customer data.

### 3.2 **User Access Management**
- **User Registration**: All users shall be **formally registered** before access is granted. Registration shall include:
  - Approval from the user’s manager.
  - Unique user ID (no shared accounts).
  - Assignment of appropriate roles/permissions.
- **User De-Registration**: Access shall be **revoked immediately** upon termination or role change.
- **Privileged Access**: Privileged accounts shall be:
  - Approved by the **CTO**.
  - Monitored and logged.
  - Reviewed **quarterly**.

### 3.3 **Authentication**
- **Passwords**:
  - Minimum length: **12 characters**.
  - Complexity: **Uppercase, lowercase, numbers, and special characters**.
  - Passwords shall be **changed every 90 days**.
  - Passwords shall **not be reused** for at least 5 cycles.
  - Passwords shall **not be shared** or written down.
- **MFA**:
  - MFA shall be enabled for all remote access and privileged accounts.
  - MFA methods: **TOTP (Time-Based One-Time Password)** or **hardware tokens**.

### 3.4 **Access Review**
- Access rights shall be **reviewed quarterly** by asset owners.
- Reviews shall be **documented** and retained for **1 year**.
- Unnecessary or excessive access shall be **revoked immediately**.

### 3.5 **Third-Party Access**
- Third-party access shall be **approved by the CTO** and **documented in contracts**.
- Third parties shall comply with this policy and the **[Supplier Security Policy](supplier_security_policy.md)**.
- Access shall be **revoked immediately** upon contract termination.

### 3.6 **Remote Access**
- Remote access shall be **secured using MFA** and **encrypted connections (VPN or SSH)**.
- Remote sessions shall be **logged and monitored**.

### 3.7 **Physical Access**
- Physical access to servers and workstations shall be **restricted to authorized personnel**.
- Access to data centers shall be **logged and reviewed quarterly**.

---

## 4. **Compliance**
- Non-compliance with this policy may result in **disciplinary action**, up to and including termination.
- Access rights may be **revoked** for non-compliance.

---

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | ISMS Owner | Initial version |
