# Cloud Security Policy

## 1. Purpose
This policy defines the information security requirements for the use of cloud services at **ACME CORP**, in alignment with **ISO 27001:2022 (Control A.5.23 — Information security for use of cloud services)**. It ensures that cloud services are adopted, configured, and operated in a manner that protects the confidentiality, integrity, and availability of Company and customer information.

---

## 2. Scope
This policy applies to all cloud services used by ACME CORP, including infrastructure (IaaS), platform (PaaS), and software (SaaS) services, regardless of whether they are used for production, development, or internal operations. It applies to all employees, contractors, and third parties who provision, configure, or use cloud services on behalf of the Company.

---

## 3. Cloud Provider Assessment and Approval

- All cloud services must be formally assessed and approved before use. Unapproved cloud services must not be used to process or store Company or customer data.
- Cloud providers must be assessed against the criteria defined in the **[Supplier Security Policy](supplier_security_policy.md)** and the **[Vendor Security Review Template](../procedures/vendor_security_review_template.md)**.
- Approved cloud providers are maintained in the asset register (see **[Asset Management Policy](asset_management_policy.md)**).
- Cloud service agreements must include provisions for security, data protection, incident notification, audit rights, and data deletion upon termination.

---

## 4. Shared Responsibility Model

- The CTO is responsible for maintaining a documented understanding of the shared responsibility model for each cloud provider in use, defining which security controls are the provider's responsibility and which are the Company's.
- Company-owned responsibilities (e.g., identity and access management, data encryption, application security, logging) must be explicitly assigned and implemented.
- Provider security certifications (e.g., ISO 27001, SOC 2) must be reviewed annually to confirm continued compliance.

---

## 5. Data Classification and Residency

- Data stored or processed in cloud environments must be classified in accordance with the **[Data Classification Policy](data_classification_policy.md)**.
- Confidential and Restricted data must only be stored in cloud regions that meet the Company's data residency requirements, including GDPR obligations for EU personal data.
- Data residency requirements must be verified before onboarding a new cloud provider or enabling a new cloud region.

---

## 6. Access Control for Cloud Environments

- Access to cloud management consoles and APIs must follow the least privilege principle, in accordance with the **[Access Control Policy](access_control_policy.md)**.
- Multi-factor authentication (MFA) is mandatory for all cloud console and administrative access.
- Root or super-admin accounts must not be used for day-to-day operations and must be secured with strong credentials and MFA.
- Access rights to cloud environments must be reviewed semi-annually and revoked promptly when no longer required.
- All access keys and API credentials must be rotated regularly and must never be hardcoded in source code or configuration files.

---

## 7. Security Configuration and Hardening

- All cloud resources must be deployed in accordance with security hardening guidelines (e.g., CIS Benchmarks for the relevant cloud provider).
- Default credentials and unnecessary services must be disabled before deployment.
- Network security controls (firewalls, security groups, private subnets) must be configured to restrict access to the minimum required.
- Infrastructure as Code (IaC) templates must be reviewed for security misconfigurations before deployment, in accordance with the **[Secure Development Policy](secure_development_policy.md)**.
- Configuration management must ensure that cloud environments remain in their approved secure state (see **[Statement of Applicability](../statement_of_applicability.md)**, A.8.9).

---

## 8. Monitoring and Logging

- Cloud activity logs (e.g., AWS CloudTrail, Azure Monitor) must be enabled for all production environments and retained for at least 90 days.
- Alerts must be configured for high-risk events, including unauthorised access attempts, changes to security configurations, and unusual data access patterns.
- Logs must be protected from tampering and must not be accessible to the accounts they monitor.
- Monitoring requirements are defined in the **[Operations Security Policy](operations_security_policy.md)**.

---

## 9. Incident Management with Cloud Providers

- In the event of a security incident involving a cloud service, the CISO must engage the cloud provider's security or incident response team as appropriate.
- Cloud provider incident notification clauses must be reviewed during onboarding to ensure timely alerting obligations are defined.
- Cloud-related incidents are managed in accordance with the **[Incident Management Policy](incident_management_policy.md)** and **[Incident Response Plan](../incident_management/incident_response_plan.md)**.

---

## 10. Exit Strategy and Portability

- Before onboarding a cloud provider, the CTO must document an exit strategy covering data export, migration, and deletion procedures.
- Cloud service agreements must include provisions for data portability and secure deletion of Company data upon contract termination.
- Data deletion by the provider must be confirmed in writing upon termination of the service.

---

## 11. Roles and Responsibilities

| Role | Responsibilities |
|------|-----------------|
| CTO (Owner) | Oversee cloud security; maintain shared responsibility documentation; approve new cloud services |
| CISO | Monitor cloud security posture; coordinate cloud-related incidents |
| Developers | Follow secure configuration and coding practices for cloud-hosted applications |
| COO | Ensure contractual security requirements are included in cloud service agreements |
| ISMS Owner | Review cloud security compliance as part of annual ISMS review |

---

## 12. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

## 13. Review and Updates
This policy will be reviewed annually or following a significant change to the Company's cloud infrastructure or a cloud-related security incident.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | ISMS Owner | Initial version |
