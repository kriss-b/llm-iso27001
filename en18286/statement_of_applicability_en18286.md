# Statement of Applicability — EN 18286 (AI Act Quality Management System)

## 1. Introduction

**EN 18286:2026** — *Artificial intelligence – Quality management system for EU AI Act regulatory purposes* — specifies a quality management system (QMS) for providers of AI systems, in support of the EU AI Act (Regulation (EU) 2024/1689). Here, "quality" means compliance with the applicable regulatory requirements, including the protection of health, safety and fundamental rights.

The QMS is operated through the AI management system ([AIMS policy](../iso42001/policies/aims_policy.md)) on top of the ISO 27001 ISMS. EN 18286 permits a QMS to extend an existing management system and to embed its quality policy in a wider policy, so this document is an **overlay** that lists what EN 18286 adds to the [ISO 42001 SoA](../iso42001/statement_of_applicability_iso42001.md), not a second management system. It maps each clause of EN 18286 to the documents already in this repository and points to the ISO 42001 documents instead of restating them.

- **Source:** EN 18286:2026, approved by CEN on 12 July 2026; cited under Commission Implementing Decision (EU) 2026/2274.
- **Out of scope:** the correspondence between EN 18286 and the AI Act (Annex ZA) is taken as granted and is not reproduced here.
- **Requirement text:** clause titles are reproduced from the standard; descriptions are paraphrased.

The **Implementation status** column uses the values defined in the [ISO 27001 Statement of Applicability](../statement_of_applicability.md).

**Cov.** rates how well the ISO 27001 base and the documents linked in the row already cover the requirement:

- 🟢 High: the requirement is covered; a cross-reference is enough.
- 🟠 Medium: a specific addition to an existing document is needed.
- 🔴 Low: new content is needed.

---

## 2. Applicability

EN 18286 is written for **providers of high-risk AI systems**: organisations that develop an AI system, or have one developed, and place it on the market or put it into service under their own name. An AI system developed in-house and used internally counts as put into service. Providers of general-purpose AI models and deployers that only use AI systems are outside its intended audience.

> **This overlay applies if the organization is a provider of high-risk AI systems.**
> _Classification basis (to be completed for the organization): AI Act role, and high-risk classification of each AI system in the [AI Systems Register](../run/registers/ai_systems_register.md)._

---

## 3. EN 18286:2026 Clause Requirements

The following table tracks implementation of the clauses of EN 18286:2026 (4–10).

| Clause | Requirement | Description | Cov. | Implementation status | Document |
|--------|-------------|-------------|------|--------|----------|
| 4.1 | General | Establish and maintain a QMS that protects health, safety and fundamental rights across the AI system life cycle. | 🟠 | ❓ TBC | [aims_policy.md](../iso42001/policies/aims_policy.md), [isms_policy.md](../policies/isms_policy.md) |
| 4.2 | Identifying regulatory requirements | Identify and systematically review the applicable regulatory requirements, and feed them into the compliance strategy. | 🟠 | ❓ TBC | [compliance_policy.md](../policies/compliance_policy.md), [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 4.3 | Determining the scope of the quality management system | Define which AI systems the QMS covers and its boundaries, from the regulatory requirements and the intended purpose. | 🟠 | ❓ TBC | [aims_policy.md](../iso42001/policies/aims_policy.md), [ai_systems_register.md](../run/registers/ai_systems_register.md) |
| 4.4 | Strategy for regulatory compliance | Define and document the compliance strategy (essential requirements, conformity assessment, data, modifications, post-market monitoring, serious incidents) and the approaches used to demonstrate each essential requirement. | 🟠 | ❓ TBC | [regulatory_compliance_strategy_policy.md](policies/regulatory_compliance_strategy_policy.md) |
| 4.5 | Documented information | Keep QMS and operational documented information controlled, version-controlled, available to authorities in an EU official language, and retained for at least the lifetime of the AI system. | 🟠 | ❓ TBC | [isms_policy.md](../policies/isms_policy.md), [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 5.1 | General | Top management shows leadership: sets the policy and objectives, provides resources, integrates the QMS into processes and holds management reviews. | 🟢 | ❓ TBC | [isms_policy.md](../policies/isms_policy.md), [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 5.2 | Quality policy | Issue a quality policy committed to regulatory compliance and to the effectiveness of the QMS, aligned with the compliance strategy and communicated to personnel. | 🟠 | ❓ TBC | [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 5.3 | Roles, responsibilities, and authorities | Assign and document QMS roles and authorities, including accountability for AI system risk management and for tracking regulatory requirements. | 🟠 | ❓ TBC | [roles_and_responsibilities_policy.md](../policies/roles_and_responsibilities_policy.md), [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 6.1 | Actions to address risks related to the functioning of the quality management system | Identify and plan actions on risks to the QMS itself, distinct from the risk management of AI systems. | 🟠 | ❓ TBC | [risk_assessment_procedure.md](../risks/risk_assessment_procedure.md), [risks_register.md](../risks/risks_register.md) |
| 6.2 | Quality objectives and planning to achieve them | Set verifiable quality objectives tied to regulatory requirements, and plan how to achieve them. | 🟠 | ❓ TBC | [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 7.1 | Resources | Provide the human, technical and infrastructure resources the QMS needs, including security of supply. | 🟢 | ❓ TBC | [isms_policy.md](../policies/isms_policy.md), [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 7.2 | Competence | Determine, ensure and document the competences needed, including understanding of regulatory requirements, intended purpose and foreseeable misuse. | 🟠 | ❓ TBC | [employee_training_procedure.md](../procedures/employee_training_procedure.md), [human_resource_security_policy.md](../policies/human_resource_security_policy.md) |
| 7.3 | Communication | Plan internal and external communication, and maintain procedures to communicate with authorities, notified bodies and other operators, including reasoned requests and notification of non-compliance, risks and serious incidents. | 🟠 | ❓ TBC | [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 7.4 | Awareness | Ensure personnel know the quality policy, their contribution to the QMS and the implications of non-conformance. | 🟢 | ❓ TBC | [employee_training_procedure.md](../procedures/employee_training_procedure.md) |
| 8.1 | Processes and procedures along the AI system lifecycle | Define processes and procedures for each life cycle stage that keep regulatory requirements met, and monitor their effectiveness. | 🟠 | ❓ TBC | [secure_ai_development_policy.md](../iso42001/policies/secure_ai_development_policy.md) |
| 8.2 | Actions to address risks of AI systems | Operate a documented risk management system over the AI system life cycle, aimed at protecting health, safety and fundamental rights. | 🟠 | ❓ TBC | [risk_assessment_procedure.md](../risks/risk_assessment_procedure.md), [ai_system_impact_assessment_template.md](../iso42001/procedures/ai_system_impact_assessment_template.md) |
| 8.3 | Inception, design and development | Determine the intended purpose; derive, review and approve complete and verifiable AI system requirements; specify the design; apply design and development controls. | 🟠 | ❓ TBC | [secure_ai_development_policy.md](../iso42001/policies/secure_ai_development_policy.md), [secure_development_policy.md](../policies/secure_development_policy.md) |
| 8.4 | Verification and validation | Verify and validate each AI system against its specification and intended purpose with documented, reproducible tests before it is placed on the market, and evaluate the residual risk. | 🟠 | ❓ TBC | [secure_ai_development_policy.md](../iso42001/policies/secure_ai_development_policy.md), [ai_system_impact_assessment_template.md](../iso42001/procedures/ai_system_impact_assessment_template.md) |
| 8.5 | Data management | Define and run data management processes, from acquisition to destruction or archiving, for training, validation, testing and other data. | 🟠 | ❓ TBC | [secure_ai_development_policy.md](../iso42001/policies/secure_ai_development_policy.md), [data_classification_policy.md](../policies/data_classification_policy.md) |
| 8.6 | Retirement | Define retirement processes and tell deployers what they must do when an AI system is retired. | 🟠 | ❓ TBC | [secure_ai_development_policy.md](../iso42001/policies/secure_ai_development_policy.md) |
| 8.7 | Identification of the AI system | Assign a unique reference to each AI system and each version assessed for conformity, linked to its technical documentation, instructions for use and datasets. | 🟠 | ❓ TBC | [ai_systems_register.md](../run/registers/ai_systems_register.md) |
| 8.8 | Continuous learning AI systems | For systems that keep learning, document and verify the predetermined changes, and cover them in risk management, technical documentation and instructions for use. | 🟠 | ❓ TBC | [ai_system_technical_documentation_template.md](../iso42001/procedures/ai_system_technical_documentation_template.md) |
| 8.9 | Product documentation | Maintain technical documentation for each AI system, drawn up before placing on the market and kept up to date, and provide instructions for use. | 🟠 | ❓ TBC | [ai_system_technical_documentation_template.md](../iso42001/procedures/ai_system_technical_documentation_template.md), [secure_ai_development_policy.md](../iso42001/policies/secure_ai_development_policy.md), [ai_system_impact_assessment_template.md](../iso42001/procedures/ai_system_impact_assessment_template.md) |
| 9.1 | Placing on the market and putting into service | Identify each AI system placed on the market or put into service in a unique way, so it can be traced afterwards. | 🟠 | ❓ TBC | [ai_systems_register.md](../run/registers/ai_systems_register.md) |
| 9.2 | Support services | Provide support services to deployers and users, including a channel for feedback on risks to health, safety and fundamental rights. | 🟠 | ❓ TBC | [ai_end_user_acceptable_use_policy.md](../iso42001/policies/ai_end_user_acceptable_use_policy.md), [ai_system_impact_assessment_template.md](../iso42001/procedures/ai_system_impact_assessment_template.md) |
| 9.3 | Supply chain | Control externally supplied products, components, models, data and services: selection criteria, monitoring, requirements and verification. | 🟠 | ❓ TBC | [supplier_security_policy.md](../policies/supplier_security_policy.md), [supplier_security_review_template.md](../procedures/supplier_security_review_template.md), [suppliers_register.md](../run/registers/suppliers_register.md) |
| 9.4 | Modifications to AI systems | Manage modifications, and decide with a documented rationale whether each one is substantial and so requires a new conformity assessment. | 🟠 | ❓ TBC | [change_management_policy.md](../policies/change_management_policy.md), [secure_ai_development_policy.md](../iso42001/policies/secure_ai_development_policy.md) |
| 9.5 | Post-market monitoring | Run a documented, active and systematic post-market monitoring system, based on a plan, that feeds performance evaluation. | 🟠 | ❓ TBC | [secure_ai_development_policy.md](../iso42001/policies/secure_ai_development_policy.md) |
| 9.6 | Reporting serious incidents | Investigate serious incidents and report them to the competent authorities within the regulatory deadlines, with procedures agreed with deployers. | 🟠 | ❓ TBC | [incident_management_policy.md](../policies/incident_management_policy.md), [incident_response_plan.md](../incidents/incident_response_plan.md) |
| 9.7 | Non-compliance | Detect, correct and analyse non-compliance and AI systems presenting a risk; inform deployers, distributors and authorities; keep records. | 🟠 | ❓ TBC | [compliance_policy.md](../policies/compliance_policy.md), [actions_register.md](../run/registers/actions_register.md), [audit_policy.md](../policies/audit_policy.md) |
| 10.1 | Management review | Review the QMS at planned intervals with top management against measurable criteria, and after a serious incident that exposes the QMS as inadequate. | 🟠 | ❓ TBC | [management_review_template.md](../procedures/management_review_template.md), [aims_policy.md](../iso42001/policies/aims_policy.md) |
| 10.2 | Planning of changes | Plan and control changes to the QMS, including when an AI system is added to its scope or substantially modified. | 🟢 | ❓ TBC | [change_management_policy.md](../policies/change_management_policy.md) |

---

## 4. Review and Updates
This SoA will be reviewed **annually**, after significant changes to the QMS or the AI systems in scope, or when a new version of EN 18286 or its citation status changes.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | CEO | Initial version |
