# Onboarding and Offboarding Procedure

## 1. Purpose
This procedure defines the information security steps to be completed when an employee or contractor joins or leaves the organization, in alignment with **ISO 27001:2022 (Controls A.6.1 — Screening, A.6.2 — Terms and conditions of employment, A.6.5 — Responsibilities after termination or change of employment, and A.5.11 — Return of assets)**.

---

## 2. Scope
This procedure applies to all employees, contractors, and third parties who are granted access to Company systems, data, or facilities.

---

## 3. Onboarding Checklist

The following steps shall be completed before or on the first day of employment.

### 3.1 Prior to Start Date

| Task | Responsible | Notes |
|------|-------------|-------|
| Conduct background screening (identity, references, criminal record where applicable) | CPO | In accordance with [Human Resource Security Policy](../policies/human_resource_security_policy.md) |
| Issue and obtain signed Employment Contract | CPO | Shall include confidentiality obligations |
| Issue and obtain signed Confidentiality / NDA Agreement | CPO | See [confidentiality_agreement_template.md](confidentiality_agreement_template.md) |
| Issue and obtain signed Acceptable Use Policy acknowledgement | CPO | See [acceptable_use_policy.md](../policies/acceptable_use_policy.md) |
| Create user account and assign role-based access rights | CTO | Follow least privilege principle |
| Provision endpoint device (laptop, mobile) with required security configuration | CTO | Encryption, MDM enrolment, anti-malware |
| Grant access to required systems only (no broad access by default) | CTO | Access justified by role |

### 3.2 On First Day

| Task | Responsible | Notes |
|------|-------------|-------|
| Provide ISMS and security policy overview | ISMS Owner | Walk through key policies |
| Complete mandatory information security awareness training | CPO | See [employee_training_procedure.md](employee_training_procedure.md) |
| Set up MFA on all assigned accounts | CTO | Mandatory for all users |
| Introduce to incident reporting process | CISO | How and where to report security events |
| Confirm physical access (office badge, key fob) is provisioned | COO | If applicable |

---

## 4. Offboarding Checklist

The following steps shall be completed on or before the employee's last day.

### 4.1 On or Before Last Day

| Task | Responsible | Notes |
|------|-------------|-------|
| Revoke all system and application access | CTO | Shall be completed by end of last working day |
| Disable user account and invalidate active sessions | CTO | Including SSO, VPN, cloud consoles |
| Revoke MFA tokens and API keys | CTO | |
| Retrieve all Company-owned equipment (laptop, mobile, access cards) | COO | Log return in asset register |
| Ensure secure wipe of returned devices | CTO | In accordance with [disposal_destruction_policy.md](../policies/disposal_destruction_policy.md) |
| Transfer ownership of files, repositories, and accounts | CTO | Ensure no critical knowledge is lost |
| Remind employee of ongoing confidentiality obligations | CPO | Reference signed NDA / employment contract |
| Revoke physical access (office badge, key fob) | COO | If applicable |
| Remove from internal mailing lists and communication tools | CPO | |

### 4.2 Within 5 Business Days of Departure

| Task | Responsible | Notes |
|------|-------------|-------|
| Confirm all access has been revoked (access rights review) | CTO | Cross-check against access register |
| Update asset register to reflect returned equipment | COO | |
| Notify relevant third-party suppliers of access changes if applicable | COO | E.g., remove from vendor portals |
| Document offboarding completion in HR records | CPO | |

---

## 5. Role Changes
When an employee changes role internally, access rights shall be reviewed and updated to reflect the new role. Access associated with the previous role — system and application access, along with any MFA tokens and API keys issued for it — shall be revoked, and active sessions invalidated. Access for the new role shall be granted following least privilege, to the systems the new role requires and no others. The account itself is not disabled.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CPO | ISMS Owner | Initial version |
