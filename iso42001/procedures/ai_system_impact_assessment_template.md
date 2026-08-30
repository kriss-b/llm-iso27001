# AI System Impact Assessment Template

**Assessment ID**: [Auto-generated]
**Date**: [YYYY-MM-DD]
**Assessor**: [Name, Role]
**Review Date**: [YYYY-MM-DD]

> Structure follows ISO/IEC 42005:2025 Clause 6 (documenting an AI system impact assessment), simplified to the fields this ISMS maintains. Complete one per AI system in the [AI Systems Register](../../run/registers/ai_systems_register.md), before deployment and at each review.

---

## AI System Information

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| AI System ID          | [Reference to the AI Systems Register] |
| System Name           |                                      |
| System version covered |                                     |
| Lifecycle stage       | [Design / Development / Pre-deployment / In operation / Change] |
| Owner                 |                                      |
| Purpose               | [Why the system exists]              |
| Functionalities and capabilities | [What it can do — outputs, autonomy, decisions it influences] |
| Intended uses         |                                      |
| Unintended or out-of-scope uses |                            |
| AI Specificity        | [Direct / Indirect]                  |

---

## Data

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| Data categories used  | [Including any personal or sensitive data] |
| Classification        | [Per [data_classification_policy.md](../../policies/data_classification_policy.md)] |
| Sources and provenance| [Where the data comes from; licensing or consent basis] |
| Known quality concerns| [Gaps, bias, staleness, representativeness] |

---

## Algorithm and Model

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| Model(s) used         | [Name and version]                   |
| Provider              | [Internal / third party — if third party, reference the [Supplier Register](../../run/registers/suppliers_register.md)] |
| Development approach  | [Off-the-shelf / fine-tuned / trained in-house] |
| Change and update handling | [How model or version changes are detected and reassessed] |

---

## Deployment Environment

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| Deployment context    | [e.g. internal tool, customer-facing product, automated decision] |
| Geographical areas    |                                      |
| Languages supported   |                                      |
| Environmental constraints | [Integrations, dependencies, operating limits] |

---

## Interested Parties

*Directly affected: the AI system acts on or about them.*

| **Party**             | **Directly affected** | **Stake or how affected** |
|-----------------------|-----------------------|---------------------------|
| Employees             |                       |                           |
| Customers             |                       |                           |
| Vulnerable groups     |                       |                           |
| Third parties / partners |                    |                           |
| Regulators            |                       |                           |
| Society / public      |                       |                           |

---

## Impacts

### Benefits

| **Potential Benefit**                     | **Who Benefits** | **Likelihood** | **Significance** | **Notes** |
|------------------------------------------|------------------|----------------|------------------|-----------|
| Improved accuracy or consistency         |                  |                |                  |           |
| Efficiency or cost reduction             |                  |                |                  |           |
| Improved accessibility or service access |                  |                |                  |           |
| [Additional benefit specific to this system] |              |                |                  |           |

### Harms

| **Potential Harm**                        | **Who is Harmed** | **Likelihood** | **Severity** | **Risk Level** | **Notes** |
|------------------------------------------|-------------------|----------------|--------------|----------------|-----------|
| Discriminatory or biased output          |                   |                |              |                |           |
| Privacy violation or data leakage        |                   |                |              |                |           |
| Incorrect or misleading output (hallucination) |             |                |              |                |           |
| Psychological harm                       |                   |                |              |                |           |
| Financial harm                           |                   |                |              |                |           |
| Environmental impact                     |                   |                |              |                |           |
| Societal harm                            |                   |                |              |                |           |
| [Additional harm specific to this system]|                   |                |              |                |           |

*Likelihood, Severity and Significance: Low / Medium / High. Risk Level derived from the [Risk Assessment Procedure](../../risks/risk_assessment_procedure.md). Risks to the organisation itself are recorded in the [Risk Register](../../risks/risks_register.md), not here.*

---

## Failure Modes and Foreseeable Misuse

| **Failure or Misuse**                     | **How it could occur** | **Resulting Harm** | **Detection** |
|------------------------------------------|------------------------|--------------------|---------------|
|                                          |                        |                    |               |
|                                          |                        |                    |               |

---

## Evaluation

| **What was tested** | **Test set or method** | **Metric** | **Result** | **Threshold met** | **Date** | **Run by** |
|---------------------|------------------------|------------|------------|-------------------|----------|------------|
|                     |                        |            |            |                   |          |            |
|                     |                        |            |            |                   |          |            |

*Cover the harms rated Medium or High above, and the intended uses. Re-run at each model or version change recorded under Algorithm and Model.*

---

## Measures

| **Addresses**         | **Measure**                          | **Owner**   | **Status**  |
|-----------------------|--------------------------------------|-------------|-------------|
| [Harm or benefit]     |                                      |             |             |
|                       |                                      |             |             |

### Human Oversight

- **Is human review required before acting on AI outputs?** ☐ Yes ☐ No
- **If yes, describe the review process:**
  ___________________________________________________________
- **Are AI decisions logged and auditable?** ☐ Yes ☐ No
- **Is the AI system disclosed to affected parties?** ☐ Yes ☐ No

---

## Information for Users

*The publishable extract of this assessment — the model card for this system. Publish this section; do not publish the rest.*

| **Field**             | **Details**                          |
|-----------------------|--------------------------------------|
| What the system does  | [Purpose and capabilities, in user terms] |
| Intended use          |                                      |
| Out-of-scope use      |                                      |
| Known limitations     | [From Harms and Failure Modes above] |
| Performance           | [Headline results from Evaluation above] |
| Human review expected | [What the user must check before acting on an output] |
| AI disclosure         | [How users are told they are interacting with an AI system] |
| Contact               | [Where to report harmful output or a vulnerability] |

---

## Conclusion and Approval

- **Overall Risk Level**: [Low / Medium / High / Critical]
- **Do the benefits justify the residual harms?** ☐ Yes ☐ No
- **Recommendation**: [Approve / Approve with conditions / Reject]
- **Conditions (if any)**:
  ___________________________________________________________

| **Role**              | **Name**          | **Signature** | **Date**    |
|-----------------------|-------------------|---------------|-------------|
| Assessor              |                   |               |             |
| CTO                   |                   |               |             |
| CISO                  |                   |               |             |

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | CEO | Initial version |
