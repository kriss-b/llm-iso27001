# Secure Development Policy

## 1. Purpose
This policy establishes requirements for integrating security throughout the software development lifecycle at **ACME CORP**. It ensures that security is addressed by design, not as an afterthought, in alignment with **ISO 27001:2022 (Control A.8.25–A.8.32)**.

---

## 2. Scope
This policy applies to:
- All employees, contractors, and third parties involved in the design, development, testing, or maintenance of software and systems.
- All software developed internally, including:
  - Customer-facing applications and APIs.
  - Internal tools and automation scripts.
  - Infrastructure-as-code and configuration management.

---

## 3. Policy Statements

### 3.1 Security by Design
- Security requirements must be defined and documented during the planning phase of any new system or feature.
- Threat modeling must be conducted for new systems and significant changes to existing ones.
- Privacy-by-design principles must be applied to all systems handling personal data.

### 3.2 Secure Coding Standards
- Developers must follow established secure coding guidelines, including **OWASP Top 10** for web applications.
- The following practices are mandatory:
  - Input validation and output encoding to prevent injection attacks.
  - Parameterised queries for all database interactions.
  - Authentication and authorisation enforced at every layer.
  - Secrets (API keys, credentials, tokens) must never be hardcoded in source code or committed to version control.

### 3.3 Dependency and Third-Party Component Management
- All third-party libraries and dependencies must be reviewed for known vulnerabilities before use.
- Dependencies must be kept up-to-date; outdated or end-of-life components must not be used in production.
- A software bill of materials (SBOM) must be maintained for critical applications.

### 3.4 Code Review
- All code changes must undergo peer review before merging into the main branch.
- Security-relevant changes (e.g., authentication, authorisation, cryptography, data handling) require review by a developer with security expertise.

### 3.5 Security Testing
- Static Application Security Testing (SAST) must be integrated into the CI/CD pipeline.
- Dynamic Application Security Testing (DAST) must be conducted before major releases.
- Penetration testing must be conducted **annually** or after significant architectural changes.

### 3.6 Secure Deployment
- All deployments must go through the change management process as defined in the **[Change Management Policy](change_management_policy.md)**.
- Production environments must be separated from development and test environments.
- Infrastructure-as-code must be reviewed for security misconfigurations before deployment.

### 3.7 Vulnerability Remediation
- Critical and high-severity vulnerabilities identified during testing must be remediated before release.
- Medium-severity vulnerabilities must be tracked and remediated within **30 days**.
- Accepted risks must be documented and approved by the CTO.

---

## 4. Roles and Responsibilities
### 4.1 CTO (Owner)
- Oversee the implementation and enforcement of this policy.
- Ensure secure development practices are embedded in engineering processes.

### 4.2 Developers
- Follow secure coding standards and participate in security training.
- Conduct peer code reviews and address identified vulnerabilities promptly.

### 4.3 IT Team
- Maintain CI/CD pipeline security tooling (SAST, dependency scanning).
- Manage separation of development, test, and production environments.

### 4.4 CISO
- Define security requirements and threat modeling standards.
- Review and approve penetration testing scope and findings.

---

## 5. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

---

## 6. Review and Updates
This policy will be reviewed **annually** or after significant changes to the technology stack, development practices, or threat landscape.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | ISMS Owner | Initial version |
