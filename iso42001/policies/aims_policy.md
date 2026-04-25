# AI Management System (AIMS) Policy

## 1. Purpose
This document defines the overarching policy governing the AI Management System (AIMS) of **ACME CORP**. It serves as the master policy for responsible AI, providing the framework within which all other AI-related policies, procedures, and controls operate.

This policy is aligned with **ISO 42001:2023 (Clauses 4, 5, 6, 8, 9 and 10)** and supports the Company's commitment to developing, deploying, and using AI systems in a responsible, transparent, and accountable manner.

---

## 2. Introduction & Objectives

ACME CORP is committed to establishing, implementing, maintaining, and continually improving its AIMS in accordance with ISO 42001:2023.

The objectives of the AIMS are to:

- Ensure AI systems are developed and operated responsibly, with fairness, transparency, and human oversight.
- Identify, assess, and treat AI-related risks and impacts in a systematic and proportionate manner.
- Ensure compliance with applicable AI regulations, including the EU AI Act and ISO 42001:2023.
- Build trust with customers, partners, and regulators through demonstrable AI governance practices.
- Foster a culture of AI safety and ethical awareness across the organisation.
- Protect individuals and society from potential harms arising from AI systems.

These objectives are reviewed at least annually as part of the management review process (see Section 10).

---

## 3. Context of the Organisation

ACME CORP develops and operates AI-powered products and services, including systems that interact with customers and process sensitive data. The Company uses and integrates third-party foundation models and AI services as part of its product offerings.

The AIMS has been designed to reflect the Company's size, AI maturity, and operational context, balancing AI governance requirements with business agility.

---

## 4. Internal & External Issues

The following issues are considered in defining the scope and objectives of the AIMS.

### 4.1 Internal Issues

| Issue | Impact on AIMS |
|-------|----------------|
| Reliance on third-party foundation models | Dependency on external providers for model governance and updates |
| Rapid AI technology evolution | Models, tools, and risks change faster than traditional software |
| Early-stage AI governance maturity | Policies and controls are being progressively implemented |
| Limited AI-specialised talent | AI governance roles may be combined with other responsibilities |
| Integration of AI across multiple products | Broad scope of AI systems requiring consistent governance |

### 4.2 External Issues

| Issue | Impact on AIMS |
|-------|----------------|
| EU AI Act and emerging AI regulations | Compliance obligations vary by AI system risk classification |
| Customer concerns about AI transparency and bias | Evidence of responsible AI practices increasingly required |
| Evolving AI threat landscape | New attack vectors (prompt injection, adversarial inputs) require ongoing attention |
| Public and societal scrutiny of AI systems | Reputational risk from harmful or biased AI outputs |
| Third-party and supply chain risks | AI model providers and data suppliers must meet governance standards |

---

## 5. Interested Parties

The following interested parties have been identified as having requirements relevant to AI management.

| Interested Party | Key Requirements |
|-----------------|-----------------|
| Customers | Transparency about AI use; protection from harmful or biased AI outputs |
| AI subjects | Right to be informed of AI decisions; ability to raise objections |
| Employees | Clear AI use policies; safe and responsible AI tools |
| Regulators (e.g., EU AI Office, CNIL) | Compliance with EU AI Act and applicable AI regulations |
| AI model providers | Clear contractual obligations on data handling and model governance |
| Investors and board | Adequate AI risk management; reputational protection |
| Civil society and advocacy groups | Ethical AI use; non-discrimination and fairness |
| Certification body | Compliance with ISO 42001:2023 requirements |

### 5.1 Contact with Authorities
The CTO and CISO are responsible for maintaining appropriate contacts with relevant AI regulatory authorities, including the EU AI Office and national competent authorities. These contacts must be activated in the event of a significant AI incident, regulatory inquiry, or when required by applicable law.

### 5.2 Contact with Special Interest Groups
The CTO is responsible for maintaining engagement with AI governance communities, standards bodies, and research organisations. This ensures the Company remains informed of emerging AI risks, best practices, and regulatory developments. Intelligence gathered through these channels feeds into the AI risk assessment process.

---

## 6. Dependencies & Interfaces

The AIMS does not operate in isolation. It interfaces with the following internal functions and external systems:

- **Legal & Compliance**: AI regulatory monitoring, contract review for AI providers, EU AI Act compliance.
- **Human Resources**: AI safety training, onboarding, and disciplinary processes.
- **Engineering & IT**: Implementation of AI technical controls, model deployment, and monitoring.
- **Finance & Procurement**: AI vendor assessment and contractual AI governance requirements.
- **Executive Leadership**: Resource allocation, risk acceptance, and strategic AI direction.
- **AI Model Providers**: Model governance, data handling obligations, and incident coordination.
- **ISMS**: The AIMS operates alongside and interfaces with the ISMS; AI-related risks feed into the shared risk register.

---

## 7. Scope of the AIMS

### 7.1 In Scope

**AI Systems**
- AI models developed or fine-tuned internally.
- Third-party AI services and APIs integrated into Company products or operations.
- AI-assisted tools used by employees to process Company or customer data.

**People**
- All employees, contractors, and third parties involved in the development, deployment, or use of AI systems.

**Locations**
- Main office (primary place of business).
- Remote workstations.
- Cloud infrastructure hosting AI systems.

### 7.2 Out of Scope
- AI systems used solely for personal purposes by employees, not involving Company data.
- Third-party products used by customers that are not integrated into Company services.

### 7.3 Justification
The AIMS covers all AI systems through which the Company could cause harm to individuals, customers, or society, or incur regulatory, reputational, or operational risk.

---

## 8. Locations

The AIMS applies to the following locations:

| Location | Type | In Scope |
|----------|------|----------|
| Main office | Primary place of business | Full scope |
| Remote working locations | Employee home offices and other remote sites | Logical controls only |
| Cloud infrastructure | Hosted by third-party providers | AI system deployment and monitoring |

---

## 9. Governance

### 9.1 AIMS Owner
The **CTO** is responsible for the overall management and performance of the AIMS. This includes coordinating AI risk assessments, managing the AI policy framework, and driving continual improvement.

### 9.2 CISO
The **CISO** is responsible for the security dimension of AI governance, including AI-specific incident response, adversarial testing standards, and AI risk register maintenance.

### 9.3 Executive Responsibility
The **CEO** provides overall leadership and ensures that adequate resources are allocated to the AIMS. The CEO approves the AIMS Policy and any significant changes to the AIMS scope or risk appetite.

### 9.4 All Employees
All employees and contractors are responsible for complying with AI policies, using AI systems responsibly, and reporting AI-related concerns or incidents promptly.

Full role definitions are documented in the **[Roles and Responsibilities Policy](../../policies/roles_and_responsibilities_policy.md)**.

---

## 10. Executive Management Review

The executive team conducts a formal **management review of the AIMS** at least once per year. The review covers:

- Results of internal audits and AI system assessments.
- Status of actions from previous reviews.
- Feedback from interested parties, including customers, regulators, and AI subjects.
- AI risk assessment results and treatment plan status.
- AI system impact assessment outcomes and open findings.
- Performance against AI management objectives.
- Changes in internal and external context that may affect the AIMS.
- Emerging AI regulations and compliance obligations.
- Opportunities for continual improvement.
- Resource adequacy.

Outputs of the management review include decisions on AIMS improvements, resource allocations, and updates to policies or objectives. Review minutes are documented and retained.

---

## 11. Activities of the AIMS

The AIMS operates through the following recurring activities:

| Activity | Frequency | Owner |
|----------|-----------|-------|
| AI risk assessment review | Annual (or after significant change) | CTO / CISO |
| AI system impact assessment | Per AI system, pre-deployment | CTO |
| AI system inventory review | Annual | CTO |
| Internal audit | Annual | CTO / CISO (see [audit_policy.md](../../policies/audit_policy.md)) |
| Management review | Annual | CEO / CTO |
| Policy and documented information review | Annual (or after significant change) | Policy owners / CTO |
| AI safety training | Annual (onboarding + refresh) | CPO |
| Supplier AI assessment | Annual | COO |
| AI system monitoring review | Quarterly | CTO |
| AI incident response exercises | Annual | CISO |

---

## 12. Description of Activities

### 12.1 AI Risk Assessment
Risks specific to AI systems are identified, assessed, and treated in accordance with the **[Risk Assessment Framework](../../risk_assessment/risk_assessment_framework.md)** and **[Risk Assessment Procedure](../../risk_assessment/risk_assessment_procedure.md)**. Results are documented in the **[Risk Register](../../risk_assessment/risk_register.md)**, with AI Specificity classified as `Indirect` or `Direct`.

### 12.2 AI System Impact Assessment
Before any AI system is deployed, an impact assessment must be completed in accordance with the **[AI System Impact Assessment Template](../procedures/ai_system_impact_assessment_template.md)**. The assessment evaluates potential harms to individuals, groups, and society, and defines mitigation measures and human oversight requirements.

### 12.3 Policy and Documented Information Management
All AIMS policies and documented information are reviewed at least annually. Policy owners are responsible for initiating reviews and obtaining approval from the CTO. Documented information must remain accurate, accessible, and fit for purpose. Version history is maintained in the Changelog of each document.

### 12.4 AI Safety Training
All employees complete AI safety training as part of the annual security awareness programme, as defined in the **[Employee Training Procedure](../../procedures/employee_training_procedure.md)**. Employees developing or operating AI systems receive additional role-specific AI governance training.

### 12.5 AI Incident Management
AI-specific incidents are managed in accordance with the **[Incident Response Plan](../../incident_management/incident_response_plan.md)**. AI incidents include hallucination, biased output, prompt injection, model failure, and harmful AI-generated content.

### 12.6 Supplier AI Management
Third-party AI providers and suppliers using AI to process Company data are assessed in accordance with the **[Supplier Security Policy](../../policies/supplier_security_policy.md)** and the **[Vendor Security Review Template](../../procedures/vendor_security_review_template.md)**.

### 12.7 Nonconformity and Corrective Actions
Nonconformities identified from any source (audits, incidents, management reviews, or employee feedback) must be recorded, root-caused, and resolved by the responsible owner. Corrective actions are tracked to resolution by the CTO and reported at the next management review.

### 12.8 Performance Monitoring and Measurement
The CTO monitors and measures AI management performance on an ongoing basis. Key inputs include AI system monitoring results, incident metrics, impact assessment outcomes, training completion rates, and audit findings. Results are consolidated and presented at the annual management review.

### 12.9 Continual Improvement
Improvement opportunities are identified from all AIMS activities, including audits, incidents, risk assessments, management reviews, and performance monitoring. The CTO maintains a log of improvement opportunities, prioritises them based on risk and impact, and tracks their implementation.

---

## 13. Risks of the AIMS

The following risks to the effective operation of the AIMS have been identified:

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|------------|
| Insufficient AI governance expertise | Medium | High | Role-specific AI training; external advisory when needed |
| Rapid AI model changes outpacing governance | High | High | AI change management process; pre-deployment impact assessments |
| Low AI safety awareness among staff | Medium | Medium | Mandatory annual AI safety training |
| Dependency on third-party AI providers | Medium | High | Supplier AI assessments; contractual obligations |
| Failure to keep AI policies current with regulation | Medium | High | Annual review cycle tied to regulatory monitoring |

---

## 14. Opportunities of the AIMS

The following opportunities have been identified through the operation of the AIMS:

- **Customer trust and competitive differentiation**: ISO 42001 certification demonstrates responsible AI governance to enterprise customers and regulators.
- **Reduced AI incident impact**: Mature detection and response capabilities reduce the cost and reputational impact of AI incidents.
- **Regulatory readiness**: A strong AIMS simplifies compliance with the EU AI Act and future AI regulatory requirements.
- **Responsible innovation**: A governed AI framework enables faster, more confident AI adoption across the business.
- **Supplier confidence**: A certified AIMS strengthens the Company's position in AI vendor negotiations and due diligence processes.

---

## 15. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

## 16. Review and Updates
This policy will be reviewed annually or following significant changes to the organisation, its AI systems, or the regulatory landscape.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | CEO | Initial version |
