# Change Management Policy

## 1. Purpose
This policy establishes a structured approach to managing changes to information systems, processes, and services. The goal is to minimize disruption, ensure security, and maintain compliance with **ISO 27001:2022 (Control A.5.37)**.

---

## 2. Scope
This policy applies to:
- All employees, contractors, and third-party vendors.
- All changes to information systems, including:
  - Software updates and patches.
  - Hardware upgrades or replacements.
  - Network configuration changes.
  - Process or procedural changes.
  - Third-party service modifications.

---

## 3. Policy Statements
### 3.1 Change Request
- All changes shall be **documented** and **submitted** via a **Change Request Form**.
- Change requests shall include:
  - Description of the change.
  - Justification and expected benefits.
  - Risk assessment and mitigation plan.
  - Rollback plan.
  - Testing plan.

### 3.2 Change Classification
Changes are classified as follows:
| **Classification** | **Definition**                                                                 | **Approval Required**               |
|--------------------|-------------------------------------------------------------------------------|-------------------------------------|
| Standard          | Low-risk, pre-approved changes (e.g., routine patches).                      | IT Team Lead                        |
| Normal            | Moderate-risk changes (e.g., software upgrades, configuration changes).      | Change Advisory Board (CAB)         |
| Emergency         | High-risk or time-sensitive changes (e.g., security patches, outages).       | IT Manager + CISO (retrospective)   |

### 3.3 Change Advisory Board (CAB)
- The **CAB** reviews and approves **Normal** changes.
- The CAB includes representatives from IT, Security, and relevant business units.
- The CAB meets **weekly** to review change requests.

### 3.4 Testing and Validation
- All changes shall be **tested** in a non-production environment before deployment.
- Testing shall validate:
  - Functionality.
  - Security.
  - Performance.
- Test results shall be documented and approved.

### 3.5 Deployment
- Changes shall be deployed during **approved maintenance windows** to minimize disruption.
- Emergency changes may be deployed outside maintenance windows with **retrospective approval**.

### 3.6 Rollback Plan
- A **rollback plan** shall be documented for all changes.
- Rollback plans shall be tested and validated.

### 3.7 Post-Implementation Review
- Conduct a **post-implementation review** for all changes to assess success and identify lessons learned.
- Document review findings and update processes as needed.

### 3.8 Documentation
- All changes shall be documented in the **Change Log**.
- The Change Log shall include:
  - Change details.
  - Approval status.
  - Deployment status.
  - Rollback status (if applicable).

---

## 4. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | ISMS Owner | Initial version |
