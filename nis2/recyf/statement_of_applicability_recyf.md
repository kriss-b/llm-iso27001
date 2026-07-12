# Statement of Applicability — ReCyF (NIS2) Overlay

## 1. Introduction

**ReCyF (Référentiel Cyber France)** is the operational cybersecurity framework published by **ANSSI** to help entities meet their obligations under the **NIS 2 Directive** as transposed into French law. It expresses **20 security objectives**, and for each, *acceptable means of compliance*.

This document is an **overlay on the base ISO 27001 ISMS**, not a parallel system. It maps ReCyF's requirements to the controls already implemented in this ISMS and identifies the **delta** — the requirements ReCyF adds beyond ISO 27001 — so effort focuses only where the base ISMS does not already cover the objective.

- **Source:** ReCyF v2.5 (17/03/2026), © ANSSI, via MesServicesCyber. ReCyF is a **working document** pending the finalisation of the French NIS 2 transposition; requirement text and mappings may still evolve.
- **Coverage ratings** (ISO 27001/27002 vs ReCyF) are taken from ANSSI's own published comparator.

---

## 2. Entity classification

NIS 2 classifies regulated entities as **Important Entities (EI)** or **Essential Entities (EE)** based on **sector and size thresholds** — a legal determination made *before* any control selection. The applicable ReCyF measures follow directly from that classification.

> **This overlay is scoped to an Important Entity (EI).**
> _Classification basis (to be completed for the organization): sector, headcount, turnover / balance-sheet against the NIS 2 transposition thresholds._

Consequently, **objectives 16–20 and all EE-only measures are out of scope** by classification, not by risk-based exclusion. Only objectives **1–15** and their **EI/EE-shared measures** apply.

---

## 3. How to read this overlay

Each in-scope measure is rated by how well the base ISO 27001 ISMS already covers it:

| Rating | Meaning | Action |
|---|---|---|
| 🟢 **High** | Base ISMS already satisfies the intent | Cross-reference only — no new work |
| 🟠 **Medium** | Theme covered, but ReCyF pins a specific frequency / ANSSI-conformity / scope | Usually a one-line addition to an existing base document |
| 🔴 **Low** | ISO 27001 does not cover it | Genuine gap — new content required |

**Base ISMS changes are deferred.** Where a measure requires a change to a base ISO 27001 document, that change is **not made here**; it is captured by the corresponding **ReCyF check** (`nis2/recyf/checks/`), which verifies the base ISMS and fails until the gap is closed.

The table below lists the **delta measures** (🔴 Low + 🟠 Medium). The remaining EI measures are rated 🟢 High and are considered satisfied by the base ISMS via their mapped ISO controls; their full enumeration is pending (see §5).

---

## 4. Delta crosswalk (EI — objectives 1–15)

| Measure | Cov. | ReCyF requirement (summary) | Base ISMS location | Status |
|---|---|---|---|---|
| 1.2 | 🔴 | List which information systems are *not* exposed to the objective's risks, with justification | scope of [assets_register.md](../../run/registers/assets_register.md) | ❓ TBC |
| 1.3 | 🔴 | Validate and review the IS list **at least annually** | [assets_register.md](../../run/registers/assets_register.md), [asset_management_policy.md](../../policies/asset_management_policy.md) | ❓ TBC |
| 2.C.3 | 🔴 | Justify any alternative measures to ANSSI in the compliance analysis | [compliance_policy.md](../../policies/compliance_policy.md) | ❓ TBC |
| 3.A.2 | 🔴 | Maintain a contact point for each ecosystem entry | [suppliers_register.md](../../run/registers/suppliers_register.md) | ❓ TBC |
| 10.A.4 | 🔴 | No account required for public-facing information systems | [access_control_policy.md](../../policies/access_control_policy.md) | ❓ TBC |
| 11.B.1 | 🔴 | Patch identity/resource directories without undue delay | [patch_management_procedure.md](../../procedures/patch_management_procedure.md) | ❓ TBC |
| 14.1 | 🔴 | Define and maintain a **cyber crisis management** procedure | **gap** — distinct from [incident_response_plan.md](../../incidents/incident_response_plan.md) | ❓ TBC |
| 14.2 | 🔴 | Keep an up-to-date **printed** list of crisis-callable persons + contacts | [emergency_contacts_register.md](../../run/registers/emergency_contacts_register.md) | ❓ TBC |
| 14.3 | 🔴 | Ensure that list is accessible in a format fit for the crisis (paper/digital) | [emergency_contacts_register.md](../../run/registers/emergency_contacts_register.md) | ❓ TBC |
| 14.5 | 🔴 | Run post-exercise / post-crisis feedback to capture improvements | **gap** — crisis procedure | ❓ TBC |
| 3.A.1 | 🟠 | Maintain an ecosystem map (IT providers/suppliers + interconnections) | [suppliers_register.md](../../run/registers/suppliers_register.md), [supplier_security_policy.md](../../policies/supplier_security_policy.md) | ❓ TBC |
| 4.1 | 🟠 | Formal IS **usage charter**, enforceable against all users | [acceptable_use_policy.md](../../policies/acceptable_use_policy.md) | ❓ TBC |
| 7.B.3 | 🟠 | **Default-deny** filtering; only required flows authorised | [communication_security_policy.md](../../policies/communication_security_policy.md) | ❓ TBC |
| 7.B.4 | 🟠 | Border firewall(s) between own IS and third-party IS | [communication_security_policy.md](../../policies/communication_security_policy.md) | ❓ TBC |
| 7.B.5 | 🟠 | Review filtering rules **at least annually** | [communication_security_policy.md](../../policies/communication_security_policy.md) | ❓ TBC |
| 8.1 | 🟠 | Remote-access encryption **conforming to ANSSI recommendations** | [cryptography_policy.md](../../policies/cryptography_policy.md), [communication_security_policy.md](../../policies/communication_security_policy.md) | ❓ TBC |
| 8.2 | 🟠 | Remote-access authentication, incl. **service providers** | [access_control_policy.md](../../policies/access_control_policy.md) | ❓ TBC |
| 10.A.6 | 🟠 | Periodic (**≥ annual**) account review | [access_control_policy.md](../../policies/access_control_policy.md), [access_review_log.md](../../run/logs/access_review_log.md) — likely already met (quarterly) | ❓ TBC |
| 14.4 | 🟠 | Crisis-specific directory of external stakeholders | [emergency_contacts_register.md](../../run/registers/emergency_contacts_register.md) | ❓ TBC |
| 15.1 | 🟠 | Cyber-crisis **tabletop exercise** at a defined frequency | [business_continuity_plan.md](../../procedures/business_continuity_plan.md) | ❓ TBC |

---

## 5. High-coverage measures (🟢) — pending enumeration

The remaining EI/EE-shared measures across objectives 1–15 are rated 🟢 High coverage by ANSSI's comparator and are considered satisfied by the base ISO 27001 ISMS via their mapped Annex A controls. Their full row-by-row enumeration will be generated from the ReCyF source data (see the source note) and added here.

---

## 6. Source & attribution

Requirement text and ISO 27001/27002 coverage ratings are sourced from **ANSSI's ReCyF v2.5** and its official comparator (MesServicesCyber). © ANSSI. This overlay is an independent mapping onto this ISMS and is not endorsed by ANSSI.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 0.1 | TBD | CISO | ISMS Owner | Initial ReCyF (NIS2) EI overlay scaffold — delta crosswalk |
