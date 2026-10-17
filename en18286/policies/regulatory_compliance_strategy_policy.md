# Regulatory Compliance Strategy Policy

## Purpose
This policy sets the Company's strategy for complying with the regulatory requirements that apply to the AI systems it provides, in alignment with **EN 18286:2026 (Clause 4.4 — Strategy for regulatory compliance)**. It is the high-level approach; the methods and measures for each AI system are recorded in its [technical documentation](../../iso42001/procedures/technical_documentation_template.md).

---

## Scope
This policy applies to:
- All AI systems in the scope of the quality management system, as recorded in the [AI Systems Register](../../run/registers/ai_systems_register.md).
- The regulatory requirements identified under the [Compliance Policy](../../policies/compliance_policy.md).

---

## Policy Statements

### Inputs
Before design starts, the following shall be determined for each AI system and recorded in its technical documentation:
- Its intended purpose.
- Its application area (the high-risk area of AI Act Annex III, or the product legislation of Annex I it falls under).
- The conformity assessment procedure it requires.

### Strategy Elements
- **Essential requirements:** each applicable essential requirement shall be met by one of the approaches below.
- **Conformity assessment:** the procedure required by AI Act Article 43 shall be selected for each AI system and followed before it is placed on the market or put into service.
- **Data management:** data used for training, validation and testing shall be managed under the [Secure AI Development Policy](../../iso42001/policies/secure_ai_development_policy.md) and the [Data Classification Policy](../../policies/data_classification_policy.md).
- **Modifications:** changes shall be managed under the [Change Management Policy](../../policies/change_management_policy.md). Each modification shall be assessed for whether it is substantial, and the decision recorded in the technical documentation; a substantial modification requires a new conformity assessment.
- **Post-market monitoring:** each AI system shall be monitored after placing on the market under a post-market monitoring plan.
- **Serious incidents:** serious incidents shall be handled and reported under the [Incident Management Policy](../../policies/incident_management_policy.md) and the [Incident Response Plan](../../incidents/incident_response_plan.md).

### Essential Requirements

| **Essential requirement** | **AI Act** | **Default approach** |
|---------------------------|------------|----------------------|
| Risk management system    | Article 9  |                      |
| Data and data governance  | Article 10 |                      |
| Technical documentation   | Article 11 |                      |
| Record-keeping            | Article 12 |                      |
| Transparency and provision of information to deployers | Article 13 | |
| Human oversight           | Article 14 |                      |
| Accuracy, robustness and cybersecurity | Article 15 |         |

*Approaches: harmonised standard cited in the Official Journal; common specification adopted in an implementing act; other standard; other technical specification. Harmonised standards are preferred where cited, as they give a presumption of conformity.*

### Documenting Measures
- The approach used for each essential requirement shall be recorded in the technical documentation of each AI system.
- Where an essential requirement is met by another standard or technical specification, or a harmonised standard applied does not cover it in full, the technical documentation shall state what is not covered and describe in detail the measures that meet it.

---

## Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

---

## Review and Updates
This policy will be reviewed **annually**, when an AI system is added to the scope of the quality management system, or when a harmonised standard or common specification relevant to an essential requirement is cited or withdrawn.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | CEO | Initial version |
