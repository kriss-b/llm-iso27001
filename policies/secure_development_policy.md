# Secure Development Policy

## 1. Purpose
This policy establishes requirements for integrating security throughout the software development lifecycle. It ensures that security is addressed by design, not as an afterthought, in alignment with **ISO 27001:2022 (Control A.8.25–A.8.32)**.

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
- Security requirements shall be defined and documented during the planning phase of any new system or feature.
- Threat modeling shall be conducted for new systems and significant changes to existing ones.
- Privacy-by-design principles shall be applied to all systems handling personal data.

### 3.2 Secure Coding Standards
- Developers shall follow established secure coding guidelines, including **OWASP Top 10** for web applications.
- The following practices are mandatory:
  - Input validation and output encoding to prevent injection attacks.
  - Parameterised queries for all database interactions.
  - Authentication and authorisation enforced at every layer.
  - Secrets (API keys, credentials, tokens) shall never be hardcoded in source code or committed to version control.

### 3.3 Dependency and Third-Party Component Management
- All third-party libraries and dependencies shall be reviewed for known vulnerabilities before use.
- Dependencies shall be kept up-to-date; outdated or end-of-life components shall not be used in production.
- A software bill of materials (SBOM) shall be maintained for critical applications.

### 3.4 Code Review
- All code changes shall undergo peer review before merging into the main branch.
- Security-relevant changes (e.g., authentication, authorisation, cryptography, data handling) require review by a developer with security expertise.

### 3.5 Security Testing
- Static Application Security Testing (SAST) shall be integrated into the CI/CD pipeline.
- Dynamic Application Security Testing (DAST) shall be conducted before major releases.
- Penetration testing shall be conducted **annually** or after significant architectural changes.

### 3.6 Secure Deployment
- All deployments shall go through the change management process as defined in the **[Change Management Policy](change_management_policy.md)**.
- Production environments shall be separated from development and test environments.
- Infrastructure-as-code shall be reviewed for security misconfigurations before deployment.

### 3.7 Vulnerability Remediation
- Critical and high-severity vulnerabilities identified during testing shall be remediated before release.
- Medium-severity vulnerabilities shall be tracked and remediated within **30 days**.
- Accepted risks shall be documented and approved by the CTO.

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
