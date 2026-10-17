# AI System Technical Documentation Template

**AI System ID**: [Reference to the AI Systems Register]
**Version**: [Version covered by this documentation]
**Date**: [YYYY-MM-DD]
**Owner**: [Name, Role]
**Review Date**: [YYYY-MM-DD]

> Structure follows Annex IV of the EU AI Act, as required by Article 11 and EN 18286 8.9.2; section numbers match Annex IV. Complete one per AI system and version in the [AI Systems Register](../../run/registers/ai_systems_register.md), before it is placed on the market or put into service, and update it when a modification affects compliance. Write "N/A" with a reason for any point that does not apply.
>
> An SME or SMC may use the Commission's simplified technical documentation form instead. For an AI system related to a product covered by Annex I, Section A, draw up a single set of documentation that also contains the information required by that legislation.

---

## 1. General Description

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| (a) Intended purpose  | [As recorded in the [AI Systems Register](../../run/registers/ai_systems_register.md)] |
| (a) Provider          |                                      |
| (a) Version and relation to previous versions | |
| (b) Interaction with external hardware or software | [Including other AI systems not part of this one] |
| (c) Software and firmware versions | [And any requirements related to version updates] |
| (d) Forms placed on the market or put into service | [e.g. embedded software, download, API] |
| (e) Target hardware   |                                      |
| (f) Product images    | [If the AI system is a component of products: external features, marking, internal layout] |
| (g) Deployer user interface | [Basic description]            |
| (h) Instructions for use | [Link to the instructions for use] |

---

## 2. Elements and Development Process

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| (a) Development methods and steps | [Including third-party pre-trained systems or tools, and how they were used, integrated or modified — see the [Supplier Register](../../run/registers/suppliers_register.md)] |
| (b) Design specifications | [General logic and algorithms; key design choices, rationale and assumptions, including about the persons or groups the system is used on; main classification choices; what the system optimises for and the relevance of its parameters; expected output and output quality; trade-offs made to meet the requirements] |
| (c) System architecture | [How software components build on or feed into each other; computational resources used to develop, train, test and validate] |
| (d) Data requirements | [Datasheets: training methods and techniques; training datasets, their provenance, scope and main characteristics; how data was obtained and selected; labelling and cleaning — see the Data section of the [impact assessment](../../iso42001/procedures/ai_system_impact_assessment_template.md)] |
| (e) Human oversight   | [Assessment of the oversight measures needed, and of the technical measures that help deployers interpret outputs — see the Human Oversight section of the [impact assessment](../../iso42001/procedures/ai_system_impact_assessment_template.md)] |
| (g) Validation and testing | [Procedures; validation and testing data and their main characteristics; metrics for accuracy, robustness, other requirements and potentially discriminatory impacts; link to the test logs and reports, dated and signed by the responsible persons, including for pre-determined changes] |
| (h) Cybersecurity measures | [See the [Secure AI Development Policy](../../iso42001/policies/secure_ai_development_policy.md) and the [Secure Development Policy](../../policies/secure_development_policy.md)] |

### (f) Pre-determined Changes

*For AI systems that continue to learn after being placed on the market or put into service (EN 18286 8.8). Otherwise write "N/A — the system does not learn after deployment".*

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| How the system learns and changes in operation | |
| Pre-determined changes and their effect on performance | |
| Data used for continuous learning |                         |
| Technical solutions ensuring continued compliance | |

---

## 3. Monitoring, Functioning and Control

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| Capabilities and limitations | [Including accuracy for specific persons or groups, and the overall expected accuracy for the intended purpose] |
| Foreseeable unintended outcomes and sources of risk | [To health, safety and fundamental rights, and discrimination — see the Harms and Failure Modes sections of the [impact assessment](../../iso42001/procedures/ai_system_impact_assessment_template.md)] |
| Human oversight measures | [Including the technical measures that help deployers interpret outputs] |
| Input data specifications |                                  |

---

## 4. Appropriateness of Performance Metrics

[Why the metrics used are appropriate for this AI system]

---

## 5. Risk Management System

[Description of the risk management system for this AI system — link the [impact assessment](../../iso42001/procedures/ai_system_impact_assessment_template.md) and the relevant entries of the [Risk Register](../../risks/risks_register.md)]

---

## 6. Changes Through the Lifecycle

[Relevant changes made by the provider, and the decision on whether each was a substantial modification — link the change records kept under the [Change Management Policy](../../policies/change_management_policy.md)]

---

## 7. Standards Applied

| **Standard or specification** | **Applied in full or in part** | **OJ reference** |
|-------------------------------|--------------------------------|------------------|
| EN 18286:2026                 |                                |                  |
|                               |                                |                  |

*Where no harmonised standard was applied, describe the solutions adopted to meet the requirements, and list the other standards and technical specifications applied.*

---

## 8. EU Declaration of Conformity

[Link to the signed copy]

---

## 9. Post-market Monitoring

[Description of the system that evaluates the AI system's performance after placing on the market — link to the post-market monitoring plan]

---

## Approval

| **Role**              | **Name**          | **Signature** | **Date**    |
|-----------------------|-------------------|---------------|-------------|
| Owner                 |                   |               |             |
| CTO                   |                   |               |             |

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | CEO | Initial version |
