# Audit Policy

## 1. Purpose
This policy defines the framework for planning, conducting, and following up on audits of the Information Security Management System (ISMS) at **ACME CORP**. It ensures that the ISMS is regularly reviewed for effectiveness, conformance, and continual improvement, in alignment with **ISO 27001:2022 (Clause 9.2 — Internal audit, A.5.35 — Independent review of information security, and A.8.34 — Protection of information systems during audit testing)**.

---

## 2. Scope
This policy applies to:
- Internal audits of the ISMS and its supporting policies and procedures.
- Technical audits, including vulnerability assessments and penetration testing.
- Compliance audits against legal, regulatory, and contractual requirements.
- Supplier audits assessing third-party security practices.
- Independent external reviews of the ISMS.

---

## 3. Types of Audits

| Audit Type | Description | Frequency |
|------------|-------------|-----------|
| Internal ISMS audit | Reviews conformance of the ISMS with ISO 27001:2022 requirements and internal policies | Annual |
| Technical audit | Vulnerability assessment and/or penetration testing of systems and applications | Annual |
| Compliance audit | Reviews adherence to legal, regulatory, and contractual obligations (e.g., GDPR) | Annual |
| Supplier audit | Reviews security practices of critical third-party suppliers | Annual or upon significant change |
| Independent review | External assessment of the ISMS by a qualified third party | At least every 2 years |

---

## 4. Audit Programme

The ISMS Owner is responsible for maintaining an **annual audit programme** that defines:
- The audits to be conducted during the year.
- The scope and objectives of each audit.
- The criteria against which the audit will be conducted.
- The planned dates and assigned auditors.

The audit programme is reviewed and approved at the annual management review. It may be updated during the year in response to significant incidents, organisational changes, or risk assessment outcomes.

---

## 5. Audit Execution

### 5.1 Auditor Independence
Auditors must be independent of the area being audited. Internal staff may conduct ISMS audits provided they do not audit their own work. External auditors are preferred for independent reviews and penetration testing.

### 5.2 Methodology
Auditors shall:
- Review documented information (policies, procedures, records, logs).
- Interview relevant personnel.
- Observe processes and controls in operation where applicable.
- Test technical controls where in scope (subject to Section 9).

### 5.3 Evidence Collection
All audit evidence must be collected, recorded, and retained in a manner that supports the audit findings. Evidence must be sufficient, relevant, and reliable.

---

## 6. Audit Reporting

### 6.1 Findings Classification
Audit findings are classified as follows:

| Classification | Definition |
|----------------|------------|
| **Non-conformity (Major)** | Absence or total breakdown of a required control or process |
| **Non-conformity (Minor)** | Partial failure or isolated lapse in a required control or process |
| **Observation** | A weakness or area for improvement that does not yet constitute a non-conformity |
| **Positive finding** | Evidence of effective implementation or best practice |

### 6.2 Audit Report
A written audit report must be produced for every audit. It shall include:
- Audit scope, objectives, and criteria.
- Summary of findings by classification.
- Evidence referenced for each finding.
- Recommendations for corrective action.

### 6.3 Distribution
Audit reports are distributed to the ISMS Owner, CISO, and relevant process owners. A summary is presented at the next management review.

---

## 7. Corrective Actions

### 7.1 Response to Non-conformities
For each non-conformity identified, the responsible process owner must:
- Investigate the root cause.
- Define and implement corrective actions.
- Verify the effectiveness of the corrective action.

### 7.2 Timelines

| Classification | Target Resolution |
|----------------|------------------|
| Major non-conformity | Within 30 days |
| Minor non-conformity | Within 90 days |
| Observation | Within 6 months or next audit cycle |

### 7.3 Escalation
Non-conformities not resolved within the target timeline are escalated to executive management and tracked at the management review.

---

## 8. Independent Review

An independent review of the ISMS is conducted by a qualified external party at least every two years, or following a significant security incident or major organisational change. The review assesses:
- The overall design and effectiveness of the ISMS.
- Conformance with ISO 27001:2022.
- Adequacy of risk management and control implementation.

Findings from the independent review are treated with the same corrective action process as internal audit findings.

---

## 9. Protection of Systems During Audit Testing

To prevent audit activities from disrupting or compromising production systems:

- Technical audits (e.g., penetration tests, vulnerability scans) must be formally scoped and authorised in writing by the CTO before commencement.
- Testing must not be conducted directly against production systems unless explicitly approved and scheduled during a low-risk window.
- A rollback or incident response plan must be in place before any intrusive testing begins.
- Any unintended impact on systems during audit testing must be reported immediately to the CISO and treated as a security incident.
- Audit tools and access credentials must be revoked and removed upon completion of testing.

---

## 10. Roles and Responsibilities

| Role | Responsibilities |
|------|-----------------|
| ISMS Owner | Maintain the audit programme; coordinate internal audits; report findings to management |
| CISO | Support technical audits; manage corrective actions for technical findings |
| CTO | Authorise and oversee technical audits; ensure system protection during testing |
| Process owners | Cooperate with auditors; implement and verify corrective actions within their area |
| External auditors | Conduct independent reviews and penetration tests in accordance with agreed scope |

---

## 11. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

## 12. Review and Updates
This policy will be reviewed annually or following a significant audit finding or organisational change.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | ISMS Owner | ISMS Owner | Initial version |
