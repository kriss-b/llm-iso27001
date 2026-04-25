# Statement of Applicability — ISO 42001:2023 (SoA)

## 1. Introduction
This **Statement of Applicability (SoA)** identifies the controls from **Annex A of ISO 42001:2023** that are applicable to **ACME CORP** and justifies their inclusion or exclusion. It also tracks the implementation status and the document(s) that implement each control. This document is a key artefact of the **AI Management System (AIMS)**.

---

## 2. Scope
This SoA applies to all AI systems developed, deployed, or used within the scope of the AIMS, including:
- AI models developed internally.
- Third-party AI services and APIs integrated into Company products or operations.
- AI-assisted tools used by employees to process Company data.

---

## 3. ISO 42001:2023 Clause Requirements

The following table tracks implementation of the mandatory ISO 42001:2023 clauses (4–10).

| Clause | Requirement | Status | Document |
|--------|-------------|--------|----------|
| 4.1 | Understanding the organization and its context (AI perspective) | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 4.2 | Understanding the needs and expectations of interested parties (AI perspective) | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 4.3 | Determining the scope of the AIMS | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 4.4 | AI management system | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 5.1 | Leadership and commitment to the AIMS | ❓ TBC | [ai_policy.md](policies/ai_policy.md) |
| 5.2 | Establish an AI Policy | ❓ TBC | [ai_policy.md](policies/ai_policy.md) |
| 5.3 | Organizational roles, responsibilities and authorities for AI | ❓ TBC | [roles_and_responsibilities_policy.md](../../policies/roles_and_responsibilities_policy.md), [ai_policy.md](policies/ai_policy.md) |
| 6.1.1 | Actions to address AI risks and opportunities — General | ❓ TBC | [risk_assessment_framework.md](../../risk_assessment/risk_assessment_framework.md) |
| 6.1.2 | AI risk assessment | ❓ TBC | [risk_assessment_framework.md](../../risk_assessment/risk_assessment_framework.md), [risk_assessment_procedure.md](../../risk_assessment/risk_assessment_procedure.md) |
| 6.1.3 | AI risk treatment | ❓ TBC | [risk_assessment_framework.md](../../risk_assessment/risk_assessment_framework.md) |
| 6.1.4 | AI system impact assessment | ❓ TBC | [ai_system_impact_assessment_template.md](procedures/ai_system_impact_assessment_template.md) |
| 6.2 | AI objectives and planning to achieve them | ❓ TBC | [ai_policy.md](policies/ai_policy.md) |
| 7.1 | Resources for the AIMS | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 7.2 | Competence for AI governance | ❓ TBC | [employee_training_procedure.md](../../procedures/employee_training_procedure.md) |
| 7.3 | Awareness of AI risks and responsibilities | ❓ TBC | [employee_training_procedure.md](../../procedures/employee_training_procedure.md), [human_resource_security_policy.md](../../policies/human_resource_security_policy.md) |
| 7.4 | Communication on AI management | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 7.5 | Documented information for the AIMS | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 8.1 | Operational planning and control of AI systems | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 8.2 | AI risk assessment (operational) | ❓ TBC | [risk_register.md](../../risk_assessment/risk_register.md) |
| 8.3 | AI risk treatment (operational) | ❓ TBC | [risk_register.md](../../risk_assessment/risk_register.md) |
| 8.4 | AI system impact assessment (operational) | ❓ TBC | [ai_system_impact_assessment_template.md](procedures/ai_system_impact_assessment_template.md) |
| 9.1 | Monitoring, measurement, analysis and evaluation of the AIMS | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 9.2 | Internal audit of the AIMS | ❓ TBC | [audit_policy.md](../../policies/audit_policy.md) |
| 9.3 | Management review of the AIMS | ❓ TBC | [management_review_template.md](../../procedures/management_review_template.md) |
| 10.1 | Nonconformity and corrective action | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |
| 10.2 | Continual improvement of the AIMS | ❓ TBC | [aims_policy.md](policies/aims_policy.md) |

---

## 4. Annex A Controls

### A.2 Policies for AI

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.2.2 | AI policy for the organization | ❓ TBC | Mandatory governance anchor for the AIMS. | [ai_policy.md](policies/ai_policy.md) |

### A.3 Internal Organization

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.3.2 | AI roles and responsibilities | ❓ TBC | Ensures accountability for AI governance across the organization. | [roles_and_responsibilities_policy.md](../../policies/roles_and_responsibilities_policy.md), [ai_policy.md](policies/ai_policy.md) |
| A.3.3 | Reporting of concerns related to AI systems | ❓ TBC | Enables employees and third parties to raise AI-related concerns safely. | [incident_response_plan.md](../../incident_management/incident_response_plan.md) |

### A.4 Resources for AI Systems

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.4.2 | AI resources | ❓ TBC | Ensures adequate technical and human resources are allocated for AI governance. | [ai_policy.md](policies/ai_policy.md) |

### A.5 Assessing Impacts of AI Systems

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.5.2 | Process for assessing AI system impact | ❓ TBC | Mandatory — evaluates potential harms to individuals, groups, and society before deployment. | [ai_system_impact_assessment_template.md](procedures/ai_system_impact_assessment_template.md) |
| A.5.3 | Documenting AI system impact assessment | ❓ TBC | Ensures impact assessments are recorded and auditable. | [ai_system_impact_assessment_template.md](procedures/ai_system_impact_assessment_template.md) |

### A.6 AI System Lifecycle

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.6.1 | General — lifecycle approach to AI systems | ❓ TBC | Ensures AI systems are governed across their full lifecycle. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.6.2 | AI system design | ❓ TBC | Integrates responsible AI principles from the design phase. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.6.3 | Data for AI systems (development phase) | ❓ TBC | Ensures data used in development is appropriate and documented. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.6.4 | Acquisition of AI system components | ❓ TBC | Controls security and quality of third-party AI components. | [supplier_security_policy.md](../../policies/supplier_security_policy.md) |
| A.6.5 | AI system operation | ❓ TBC | Ensures AI systems operate within defined parameters and constraints. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.6.6 | AI system documentation | ❓ TBC | Ensures AI systems are sufficiently documented for users and auditors. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.6.7 | AI system testing | ❓ TBC | Validates AI system behaviour, including edge cases and bias, before deployment. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.6.8 | AI system monitoring | ❓ TBC | Detects drift, degradation, or unexpected behaviour in production. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.6.9 | Change management of AI systems | ❓ TBC | Controls changes to AI models, prompts, and configurations. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.6.10 | Decommissioning of AI systems | ❓ TBC | Ensures AI systems are retired securely and data is disposed of appropriately. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |

### A.7 Data for AI Systems

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.7.2 | Data management policies | ❓ TBC | Establishes governance for all data used in AI systems. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.7.3 | Data acquisition | ❓ TBC | Ensures data is acquired lawfully and ethically. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.7.4 | Data quality | ❓ TBC | Ensures training and evaluation data meets quality standards. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.7.5 | Data preparation | ❓ TBC | Controls data preprocessing to prevent bias introduction or data leakage. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.7.6 | Data provenance | ❓ TBC | Ensures origin and lineage of AI data is documented and traceable. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.7.7 | Data pertaining to persons | ❓ TBC | Protects personal data used in AI systems in compliance with GDPR and EU AI Act. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |
| A.7.8 | Data for testing AI systems | ❓ TBC | Ensures test datasets are representative and do not include inappropriate personal data. | [secure_ai_development_policy.md](policies/secure_ai_development_policy.md) |

### A.8 Information for Interested Parties About AI Systems

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.8.2 | Informing interested parties about AI systems | ❓ TBC | Ensures transparency with customers, employees, and regulators about AI use. | [ai_policy.md](policies/ai_policy.md) |
| A.8.3 | AI system user guidance | ❓ TBC | Provides users with the information needed to use AI systems responsibly. | |
| A.8.4 | Identification of AI-generated content | ❓ TBC | Ensures AI-generated content is disclosed where required by law or policy. | |

### A.9 Use of AI Systems

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.9.2 | Policy for use of AI systems | ❓ TBC | Defines acceptable and unacceptable use of AI systems by employees and customers. | [acceptable_use_policy.md](../../policies/acceptable_use_policy.md), [ai_policy.md](policies/ai_policy.md) |
| A.9.3 | Conditions for use of AI systems | ❓ TBC | Sets operational conditions and constraints for AI system use. | [acceptable_use_policy.md](../../policies/acceptable_use_policy.md) |
| A.9.4 | Responsible use of AI systems | ❓ TBC | Promotes ethical and responsible AI use across the organization. | [acceptable_use_policy.md](../../policies/acceptable_use_policy.md), [ai_policy.md](policies/ai_policy.md) |
| A.9.5 | Human oversight mechanisms | ❓ TBC | Ensures humans can intervene, override, or shut down AI systems when necessary. | [ai_policy.md](policies/ai_policy.md), [ai_system_impact_assessment_template.md](procedures/ai_system_impact_assessment_template.md) |
| A.9.6 | AI subjects | ❓ TBC | Provides mechanisms for individuals affected by AI decisions to raise objections. | |

### A.10 Third-Party and Customer Relationships

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.10.2 | Third-party AI system acquisition | ❓ TBC | Ensures AI systems acquired from third parties meet organizational AI governance requirements. | [supplier_security_policy.md](../../policies/supplier_security_policy.md) |
| A.10.3 | Sharing AI system information with third parties | ❓ TBC | Controls disclosure of AI system details to third parties. | [supplier_security_policy.md](../../policies/supplier_security_policy.md) |
| A.10.4 | Responsible use of AI systems by customers | ❓ TBC | Ensures customers are informed of conditions and limitations of AI systems they use. | |

---

## 5. Review and Updates
This SoA will be reviewed **annually** or after significant changes to the AIMS, AI systems in scope, or applicable regulations (e.g., EU AI Act).

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | CEO | Initial version |
