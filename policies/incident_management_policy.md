# Incident Management Policy

## 1. Purpose
This policy establishes the framework for managing information security incidents at **ACME CORP**. It ensures that incidents are detected, reported, assessed, and resolved in a timely and consistent manner, minimising their impact on the confidentiality, integrity, and availability of information assets. This policy aligns with **ISO 27001:2022 (Controls A.5.24 – A.5.28)**, which cover:

- **A.5.24** — Information security incident management planning and preparation
- **A.5.25** — Assessment and decision on information security events
- **A.5.26** — Response to information security incidents
- **A.5.27** — Learning from information security incidents
- **A.5.28** — Collection of evidence

---

## 2. Scope
This policy applies to:
- All employees, contractors, and third-party vendors.
- All information assets, systems, and processes operated by or on behalf of the Company.
- All types of information security incidents, including but not limited to:
  - Data breaches and unauthorised access.
  - Malware infections and ransomware attacks.
  - Denial-of-service attacks.
  - Phishing and social engineering.
  - Physical security breaches affecting information assets.
  - Accidental data loss or disclosure.

---

## 3. Policy Statements

### 3.1 Incident Classification
All security events must be assessed and classified according to severity:

| **Severity** | **Definition** | **Examples** |
|---|---|---|
| **Low** | Minor impact, no data loss, no regulatory implications. | Failed login attempts, minor policy violations. |
| **Medium** | Moderate impact, potential data loss, limited regulatory implications. | Suspected phishing, unauthorised access attempt. |
| **High** | Significant impact, confirmed data loss, likely regulatory implications. | Confirmed breach, ransomware infection. |
| **Critical** | Catastrophic impact, confirmed data breach, certain regulatory implications. | Mass data exfiltration, full system compromise. |

### 3.2 Reporting
- All employees must report suspected or confirmed security incidents **immediately** to the **Incident Response Team (IRT)**.
- Reports must be submitted using the **Incident Report Template** (`incident_management/incident_report_template.md`).
- No employee shall attempt to investigate or remediate an incident without IRT involvement.

### 3.3 Response
- The IRT must acknowledge all reported incidents within **1 hour**.
- Incidents must be contained, investigated, and resolved in accordance with the **[Incident Response Plan](../incident_management/incident_response_plan.md)**.
- Evidence must be preserved in a manner that maintains its integrity and chain of custody.

### 3.4 Regulatory Notification
- Data breaches involving personal data must be reported to the relevant supervisory authority within **72 hours** of discovery, in compliance with GDPR and applicable regulations.
- Affected individuals must be notified without undue delay where the breach is likely to result in a high risk to their rights and freedoms.

### 3.5 Post-Incident Review
- A post-incident review must be conducted for all **High** and **Critical** incidents within **5 business days** of resolution.
- Lessons learned must be documented and used to improve controls, procedures, and training.

### 3.6 Non-Retaliation
- Employees who report incidents in good faith are protected from retaliation.
- This protection applies regardless of whether the report results in a confirmed incident.

---

## 4. Roles and Responsibilities
### 4.1 CISO (Owner)
- Maintain and enforce this policy.
- Oversee the Incident Response Team and post-incident review process.

### 4.2 Incident Response Team (IRT)
- Receive, assess, and classify all reported incidents.
- Lead containment, investigation, and recovery activities.
- Coordinate regulatory notifications where required.

### 4.3 Employees
- Report suspected or confirmed incidents immediately.
- Cooperate fully with the IRT during investigations.
- Preserve potential evidence and avoid actions that could compromise it.

### 4.4 Managers
- Ensure their teams are aware of incident reporting obligations.
- Support the IRT during investigations affecting their area.

---

## 5. Compliance
Non-compliance with this policy, including failure to report incidents, may result in disciplinary action, up to and including termination of employment or contracts, and legal penalties where applicable.

---

## 6. Review and Updates
This policy will be reviewed **annually** or following a significant incident or changes to the regulatory environment.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CISO | ISMS Owner | Initial version |
