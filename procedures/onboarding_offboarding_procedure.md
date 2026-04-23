# Onboarding and Offboarding Procedure

## 1. Purpose
This procedure defines the information security steps to be completed when an employee or contractor joins or leaves **ACME CORP**, in alignment with **ISO 27001:2022 (Controls A.6.1 — Screening, A.6.2 — Terms and conditions of employment, A.6.5 — Responsibilities after termination or change of employment, and A.5.11 — Return of assets)**.

---

## 2. Scope
This procedure applies to all employees, contractors, and third parties who are granted access to Company systems, data, or facilities.

---

## 3. Onboarding Checklist

The following steps must be completed before or on the first day of employment.

### 3.1 Prior to Start Date

| # | Task | Responsible | Notes |
|---|------|-------------|-------|
| 1 | Conduct background screening (identity, references, criminal record where applicable) | CPO | In accordance with [Human Resource Security Policy](../policies/human_resource_security_policy.md) |
| 2 | Issue and obtain signed Employment Contract | CPO | Must include confidentiality obligations |
| 3 | Issue and obtain signed Confidentiality / NDA Agreement | CPO | See [confidentiality_agreement_template.md](confidentiality_agreement_template.md) |
| 4 | Issue and obtain signed Acceptable Use Policy acknowledgement | CPO | See [acceptable_use_policy.md](../policies/acceptable_use_policy.md) |
| 5 | Create user account and assign role-based access rights | CTO | Follow least privilege principle |
| 6 | Provision endpoint device (laptop, mobile) with required security configuration | CTO | Encryption, MDM enrolment, anti-malware |
| 7 | Grant access to required systems only (no broad access by default) | CTO | Access justified by role |

### 3.2 On First Day

| # | Task | Responsible | Notes |
|---|------|-------------|-------|
| 8 | Provide ISMS and security policy overview | ISMS Owner | Walk through key policies |
| 9 | Complete mandatory information security awareness training | CPO | See [employee_training_procedure.md](employee_training_procedure.md) |
| 10 | Set up MFA on all assigned accounts | CTO | Mandatory for all users |
| 11 | Introduce to incident reporting process | CISO | How and where to report security events |
| 12 | Confirm physical access (office badge, key fob) is provisioned | COO | If applicable |

---

## 4. Offboarding Checklist

The following steps must be completed on or before the employee's last day.

### 4.1 On or Before Last Day

| # | Task | Responsible | Notes |
|---|------|-------------|-------|
| 1 | Revoke all system and application access | CTO | Must be completed by end of last working day |
| 2 | Disable user account and invalidate active sessions | CTO | Including SSO, VPN, cloud consoles |
| 3 | Revoke MFA tokens and API keys | CTO | |
| 4 | Retrieve all Company-owned equipment (laptop, mobile, access cards) | COO | Log return in asset register |
| 5 | Ensure secure wipe of returned devices | CTO | In accordance with [disposal_destruction_policy.md](../policies/disposal_destruction_policy.md) |
| 6 | Transfer ownership of files, repositories, and accounts | CTO | Ensure no critical knowledge is lost |
| 7 | Remind employee of ongoing confidentiality obligations | CPO | Reference signed NDA / employment contract |
| 8 | Revoke physical access (office badge, key fob) | COO | If applicable |
| 9 | Remove from internal mailing lists and communication tools | CPO | |

### 4.2 Within 5 Business Days of Departure

| # | Task | Responsible | Notes |
|---|------|-------------|-------|
| 10 | Confirm all access has been revoked (access rights review) | CTO | Cross-check against access register |
| 11 | Update asset register to reflect returned equipment | COO | |
| 12 | Notify relevant third-party suppliers of access changes if applicable | COO | E.g., remove from vendor portals |
| 13 | Document offboarding completion in HR records | CPO | |

---

## 5. Role Changes
When an employee changes role internally, access rights must be reviewed and updated to reflect the new role. Access no longer required must be revoked. The steps in Section 3.1 (items 5 and 7) and Section 4.1 (items 1–3) apply as relevant.

---

## 6. Roles and Responsibilities

| Role | Responsibilities |
|------|-----------------|
| CPO | Coordinate overall onboarding/offboarding; HR documentation; training |
| CTO | Provision and revoke technical access; device management |
| CISO | Security briefing; verify access revocation |
| COO | Physical access and asset return |
| ISMS Owner | Ensure procedure is followed; periodic review |

---

## 7. Review and Updates
This procedure will be reviewed annually or following a security incident related to onboarding or offboarding.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CPO | ISMS Owner | Initial version |
