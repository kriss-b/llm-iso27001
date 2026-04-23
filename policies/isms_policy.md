# Information Security Management System (ISMS) Policy

## 1. Purpose
This document defines the overarching policy governing the Information Security Management System (ISMS) of **ACME CORP**. It serves as the master policy for information security, providing the framework within which all other information security policies, procedures, and controls operate.

This policy is aligned with **ISO 27001:2022 (Clauses 4, 5, 6, 8, 9 and 10)** and supports the Company's commitment to protecting the confidentiality, integrity, and availability of information assets.

---

## 2. Introduction & Objectives

ACME CORP is committed to establishing, implementing, maintaining, and continually improving its ISMS in accordance with ISO 27001:2022.

The objectives of the ISMS are to:

- Protect the confidentiality, integrity, and availability of customer and company information.
- Identify, assess, and treat information security risks in a systematic and proportionate manner.
- Ensure compliance with applicable legal, regulatory, and contractual requirements.
- Build trust with customers, partners, and regulators through demonstrable security practices.
- Support business continuity and resilience in the face of security incidents or disruptions.
- Foster a culture of information security awareness across the organisation.

These objectives are reviewed at least annually as part of the management review process (see Section 10).

---

## 3. Context of the Organisation

ACME CORP operates a SaaS platform. The Company processes sensitive customer data and relies on cloud infrastructure for the delivery of its services.

The ISMS has been designed to reflect the Company's size, risk profile, and operational context, balancing security requirements with business agility.

---

## 4. Internal & External Issues

The following issues are considered in defining the scope and objectives of the ISMS.

### 4.1 Internal Issues

| Issue | Impact on ISMS |
|-------|----------------|
| Small team size | Limited dedicated security resources; roles must be combined |
| Remote and hybrid working model | Increased endpoint and access control requirements |
| Reliance on cloud infrastructure | Shared responsibility model with cloud providers must be managed |
| Rapid product development pace | Security must be integrated into development processes (DevSecOps) |
| Early-stage security maturity | Policies and controls are being progressively implemented |

### 4.2 External Issues

| Issue | Impact on ISMS |
|-------|----------------|
| GDPR and data protection regulations | Strict requirements on personal data handling and breach notification |
| Customer contractual requirements | Some customers require evidence of ISO 27001 compliance |
| Evolving threat landscape | Continuous monitoring and threat intelligence required |
| Third-party and supply chain risks | Vendors and cloud providers must meet security standards |
| Regulatory requirements in target markets | Compliance obligations vary across jurisdictions |

---

## 5. Interested Parties

The following interested parties have been identified as having requirements relevant to information security.

| Interested Party | Key Requirements |
|-----------------|-----------------|
| Customers | Confidentiality and integrity of their data; evidence of security compliance |
| Employees | Clear security policies; safe and secure working environment |
| Regulators (e.g., CNIL, ICO) | Compliance with GDPR and applicable data protection laws |
| Law enforcement authorities | Cooperation in the event of a security incident or criminal investigation |
| Special interest groups (e.g., CERTs, ISACs, security communities) | Threat intelligence sharing; awareness of emerging vulnerabilities and best practices |
| Cloud and technology vendors | Clear contractual security obligations; timely incident notification |
| Investors and board | Adequate risk management; business continuity assurance |
| Certification body | Compliance with ISO 27001:2022 requirements |

### 5.1 Contact with Authorities
The ISMS Owner and CISO are responsible for maintaining appropriate contacts with relevant authorities, including data protection supervisory authorities (e.g., CNIL, ICO), law enforcement, and national cybersecurity agencies. These contacts must be activated in the event of a significant security incident, data breach, or when required by applicable law. Contact details are maintained by the Legal & Compliance function and reviewed annually.

### 5.2 Contact with Special Interest Groups
The CISO is responsible for maintaining membership of, or engagement with, relevant security special interest groups, such as national CERTs, sector-specific ISACs, and professional security communities. This ensures the Company remains informed of emerging threats, vulnerabilities, and security best practices. Threat intelligence gathered through these channels feeds into the risk assessment process.

---

## 6. Dependencies & Interfaces

The ISMS does not operate in isolation. It interfaces with the following internal functions and external systems:

- **Legal & Compliance**: Regulatory monitoring, contract review, NDA management.
- **Human Resources**: Onboarding, offboarding, training, and disciplinary processes.
- **Engineering & IT**: Implementation of technical controls, patch management, and secure development.
- **Finance & Procurement**: Vendor assessment and contractual security requirements.
- **Executive Leadership**: Resource allocation, risk acceptance, and strategic alignment.
- **Cloud Providers**: Shared responsibility model, security configurations, and incident coordination.

---

## 7. Scope of the ISMS

### 7.1 In Scope

**Systems**
- SaaS platform.
- Cloud infrastructure (AWS/Azure/GCP).
- Internal tools (e.g., CI/CD, monitoring, code repositories).
- Customer data and user accounts.
- Office network infrastructure and on-premises equipment.

**People**
- 5 engineers (development, operations, security).
- All employees of the Company.
- Third-party vendors with access to systems (e.g., payment processors, hosting providers).

**Locations**
- Main office (primary place of business).
- Remote workstations (employees working from home or other locations).
- Cloud data centers (hosting providers).

### 7.2 Out of Scope
- Physical security of employee home offices.
- Personal devices not used for work.

### 7.3 Justification
The ISMS covers all digital assets and processes critical to the SaaS platform, as well as the physical security of the main office. Remote working locations are included in scope for logical and endpoint security controls, but physical security of individual home offices is outside the Company's direct control and is therefore excluded.

---

## 8. Locations

The ISMS applies to the following locations:

| Location | Type | In Scope |
|----------|------|----------|
| Main office | Primary place of business | Full scope (physical and logical) |
| Remote working locations | Employee home offices and other remote sites | Logical and endpoint security controls only |
| Cloud data centres | Hosted by third-party providers | Logical controls and shared responsibility |

---

## 9. Governance

### 9.1 ISMS Owner
The **ISMS Owner** is responsible for the overall management and performance of the ISMS. This includes coordinating risk assessments, managing the policy framework, and driving continual improvement.

### 9.2 CISO
The **CISO** is responsible for the technical and operational implementation of the ISMS, including incident response, vulnerability management, and security monitoring.

### 9.3 Executive Responsibility
The **CEO** provides overall leadership and ensures that adequate resources are allocated to the ISMS. The CEO approves the ISMS Policy and any significant changes to the ISMS scope or risk appetite.

### 9.4 All Employees
All employees and contractors are responsible for complying with information security policies and reporting security events promptly.

Full role definitions are documented in the **[Roles and Responsibilities Policy](roles_and_responsibilities_policy.md)**.

---

## 10. Executive Management Review

The executive team conducts a formal **management review of the ISMS** at least once per year. The review covers:

- Results of internal audits and security assessments.
- Status of actions from previous reviews.
- Feedback from interested parties, including customers and regulators.
- Risk assessment results and treatment plan status.
- Performance against information security objectives.
- Changes in internal and external context that may affect the ISMS.
- Opportunities for continual improvement.
- Resource adequacy.

Outputs of the management review include decisions on ISMS improvements, resource allocations, and updates to policies or objectives. Review minutes are documented and retained.

---

## 11. Activities of the ISMS

The ISMS operates through the following recurring activities:

| Activity | Frequency | Owner |
|----------|-----------|-------|
| Risk assessment review | Annual (or after significant change) | ISMS Owner |
| Internal audit | Annual | ISMS Owner / CISO (see [audit_policy.md](audit_policy.md)) |
| Management review | Annual | CEO / ISMS Owner |
| Policy and documented information review | Annual (or after significant change) | Policy owners / ISMS Owner |
| Security awareness training | Annual (onboarding + refresh) | CPO |
| Supplier security review | Annual | COO |
| Backup and recovery testing | Quarterly | CTO |
| Incident response exercises | Annual | CISO |
| Vulnerability scanning and patching | Ongoing | CTO |
| Access rights review | Semi-annual | CTO |

---

## 12. Description of Activities

### 12.1 Risk Assessment
Risks to the confidentiality, integrity, and availability of information are identified, assessed, and treated in accordance with the **[Risk Assessment Policy](risk_assessment_policy.md)** and **[Risk Assessment Procedure](../risk_assessment/risk_assessment_procedure.md)**. Results are documented in the **[Risk Register](../risk_assessment/risk_register.md)**.

### 12.2 Internal Audit
Internal audits verify that the ISMS is implemented and maintained effectively and in conformance with ISO 27001:2022. Findings are reported to executive management and tracked to resolution.

### 12.3 Policy and Documented Information Management
All ISMS policies and documented information (procedures, plans, templates, registers, and records) are reviewed at least annually. Policy owners are responsible for initiating reviews and obtaining approval from the ISMS Owner. Documented information must be created, updated, controlled, and retained in a manner that ensures it remains accurate, accessible, and fit for purpose. Version history is maintained in the Changelog of each document.

### 12.4 Security Awareness Training
All employees complete information security awareness training upon onboarding and at least annually thereafter, as defined in the **[Employee Training Procedure](../procedures/employee_training_procedure.md)**.

### 12.5 Incident Management
Security incidents are managed in accordance with the **[Incident Management Policy](incident_management_policy.md)** and **[Incident Response Plan](../incident_management/incident_response_plan.md)**.

### 12.6 Supplier Management
Third-party suppliers with access to Company systems or data are assessed for security risks in accordance with the **[Supplier Security Policy](supplier_security_policy.md)**.

### 12.7 Nonconformity and Corrective Actions
Nonconformities identified from any source (audits, incidents, management reviews, or employee feedback) must be recorded, root-caused, and resolved by the responsible owner. Corrective actions are tracked to resolution by the ISMS Owner and reported at the next management review. Audit-related nonconformities follow the process defined in the **[Audit Policy](audit_policy.md)**.

### 12.8 Performance Monitoring and Measurement
The ISMS Owner monitors and measures information security performance on an ongoing basis. Key inputs include audit results, incident metrics, vulnerability scan outcomes, access rights review findings, and training completion rates. Results are consolidated and presented at the annual management review to evaluate whether information security objectives are being met and to identify areas for improvement.

### 12.9 Continual Improvement
Improvement opportunities are identified from all ISMS activities, including audits, incidents, risk assessments, management reviews, and performance monitoring. The ISMS Owner maintains a log of improvement opportunities, prioritises them based on risk and impact, and tracks their implementation. Progress is reviewed at each management review to ensure the ISMS remains effective, relevant, and aligned with the Company's objectives.

---

## 13. Risks of the ISMS

The following risks to the effective operation of the ISMS have been identified:

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|------------|
| Insufficient resources allocated to security | Medium | High | Annual resource review at management review |
| Key person dependency (ISMS Owner / CISO) | Medium | High | Document processes; cross-train team members |
| Low security awareness among staff | Medium | Medium | Mandatory annual training programme |
| Scope creep or unmanaged changes | Low | High | Change management policy enforced |
| Failure to keep policies up to date | Medium | Medium | Annual review cycle with assigned owners |

---

## 14. Opportunities of the ISMS

The following opportunities have been identified through the operation of the ISMS:

- **Customer trust and competitive differentiation**: ISO 27001 certification enables ACME CORP to demonstrate security maturity to enterprise customers and win business in regulated sectors.
- **Reduced incident impact**: Mature detection and response capabilities reduce the cost and reputational impact of security incidents.
- **Regulatory readiness**: A strong ISMS simplifies compliance with GDPR and future regulatory requirements.
- **Operational efficiency**: Documented processes and controls reduce ad-hoc decision-making and improve consistency.
- **Supplier confidence**: A certified ISMS strengthens the Company's position in supplier negotiations and due diligence processes.

---

## 15. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

## 16. Review and Updates
This policy will be reviewed annually or following significant changes to the organisation, its context, or the threat landscape.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | ISMS Owner | ISMS Owner | Initial version |
