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

The **Description** column reproduces ANSSI's verbatim acceptable-means-of-compliance text (© ANSSI); the **Requirement** column is the measure's theme.

**Base ISMS changes are deferred.** Where a measure requires a change to a base ISO 27001 document, that change is **not made here**; it is captured by the corresponding **ReCyF check** (`nis2/recyf/checks/`), which verifies the base ISMS and fails until the gap is closed.

The table below lists the **delta measures** (🔴 Low + 🟠 Medium). The remaining EI measures are rated 🟢 High and are considered satisfied by the base ISMS via their mapped ISO controls; their full enumeration is pending (see §5).

---

## 4. Delta crosswalk (EI — objectives 1–15)

| Measure | Requirement | Description | Cov. | Base ISMS document | Status |
|---|---|---|---|---|---|
| 1.2 | IS inventory | The entity shall specify in the list provided for in 1.1-EI/EE the information systems which are not exposed to any of the risks mentioned in paragraph 2 of the security objective.<br>The entity shall provide justifications for those choices. | 🔴 | [assets_register.md](../../run/registers/assets_register.md) | ❓ TBC |
| 1.3 | IS inventory | The entity shall validate and review annually the list set out in 1.1-EI/EE, or as necessary in particular in the event of changes to the entity's activities and services or when a new information system is put into operation. | 🔴 | [assets_register.md](../../run/registers/assets_register.md), [asset_management_policy.md](../../policies/asset_management_policy.md) | ❓ TBC |
| 2.C.3 | Compliance management | Where the entity is not required to implement the framework but decides to apply it in order to demonstrate compliance with security objectives, and where it applies one or more alternative measures to the framework's acceptable means of compliance, it must set out the reasons for doing so in its compliance analysis. ANSSI may assess the relevance of the measure adopted to satisfy the requirement of the framework that was not adopted during a control. | 🔴 | [compliance_policy.md](../../policies/compliance_policy.md) | ❓ TBC |
| 3.A.2 | Ecosystem mapping | The entity shall provide and maintain up-to-date contact details of at least one contact point for each entry in the ecosystem mapping. | 🔴 | [suppliers_register.md](../../run/registers/suppliers_register.md) | ❓ TBC |
| 10.A.4 | Identification | Where an information system is used to disseminate information to the public, the entity is not required to create accounts for public access to that information (for example: access to a showcase site does not require authentication of visitors, whereas access to the intranet must authenticate users). | 🔴 | [access_control_policy.md](../../policies/access_control_policy.md) | ❓ TBC |
| 11.B.1 | Directory security | The entity shall apply security patches to directories managing users or resources of its information systems without undue delay. | 🔴 | [patch_management_procedure.md](../../procedures/patch_management_procedure.md) | ❓ TBC |
| 14.1 | Crisis management | The entity shall ensure the definition, maintenance and implementation of a crisis management procedure in the event of a security incident on its information systems requiring a switch to crisis mode (for example: for significant incidents as defined in Article 17 of the PJL). | 🔴 | **gap** — cf. [incident_response_plan.md](../../incidents/incident_response_plan.md) | ❓ TBC |
| 14.2 | Crisis management | The entity shall ensure that a printed list of people who can be mobilized in crisis management on digital security topics, as well as their contact details, is kept up to date. | 🔴 | [emergency_contacts_register.md](../../run/registers/emergency_contacts_register.md) | ❓ TBC |
| 14.3 | Crisis management | The entity shall ensure that the list of persons who can be called upon as provided for in 14.2-EI/EE is accessible in a format appropriate to the nature of the crisis (for example, the list must be accessible in paper format if information systems are no longer available, and it must be accessible in digital format if the paper version is not accessible). | 🔴 | [emergency_contacts_register.md](../../run/registers/emergency_contacts_register.md) | ❓ TBC |
| 14.5 | Crisis management | The entity shall ensure the implementation of feedbacks to identify areas for improvement and associated measures to be implemented following a training, exercise or crisis. | 🔴 | **gap** — crisis procedure | ❓ TBC |
| 3.A.1 | Ecosystem mapping | The entity shall define and maintain a mapping of the ecosystem in which its information systems are implemented and containing, as a minimum, the following information:<br>• The list of IT providers and suppliers contributing to the performance of the entity's activities or services and with whom there is a legal or de facto relationship (for example: outsourcing provider, equipment and services provided by the parent company to a subsidiary, IT equipment supplier)<br>• The list of interconnections with the entity's information systems.<br>(This list may be based on the steps already taken by the entity to produce such a list. For example, the declaration of subcontracting carried out under a public procurement contract.) | 🟠 | [suppliers_register.md](../../run/registers/suppliers_register.md), [supplier_security_policy.md](../../policies/supplier_security_policy.md) | ❓ TBC |
| 4.1 | HR security | The entity shall define and implement a charter for the use of information systems and make it effective against each of the users of those information systems.<br>This charter may include specific provisions for directors.<br>This charter may also cover information systems for which the entity has decided not to apply the security objectives. | 🟠 | [acceptable_use_policy.md](../../policies/acceptable_use_policy.md) | ❓ TBC |
| 7.B.3 | Communications filtering | At the interconnections level, the entity shall implement filtering rules to authorise only those communications identified in measure 7.B.1-EI/EE or 7.B.2-EE. Other communications are blocked by default. | 🟠 | [communication_security_policy.md](../../policies/communication_security_policy.md) | ❓ TBC |
| 7.B.4 | Communications filtering | The entity filters at a minimum through one or more firewalls dedicated to this purpose:<br>• communications between the entity's information systems and other information systems for which it has decided to apply the security objectives or not on the one hand, and<br>• third-party information systems on the other hand.<br>For example: an entity implementing a firewall to filter communications between its information systems (for which it applies security objectives or not) on the one hand and third-party information systems on the other hand is an acceptable solution. | 🟠 | [communication_security_policy.md](../../policies/communication_security_policy.md) | ❓ TBC |
| 7.B.5 | Communications filtering | The entity shall annually review the technical implementation of the filtering rules referred to in measure 7.B.4-EI/EE. | 🟠 | [communication_security_policy.md](../../policies/communication_security_policy.md) | ❓ TBC |
| 8.1 | Remote access security | The entity shall protect access to its information systems through a third-party information system by means of encryption mechanisms that comply with the recommendations of the national information systems security authority (for example: TLS or IPSec VPN, encrypted application protocols like TLS, SSH, etc.) | 🟠 | [cryptography_policy.md](../../policies/cryptography_policy.md), [communication_security_policy.md](../../policies/communication_security_policy.md) | ❓ TBC |
| 8.2 | Remote access security | When the access referred to in measure 8.2-EI/EE are carried out by authorised personnel and service providers, the entity shall protect access to information systems through an authentication mechanism that complies with the measures relating to Authentication. | 🟠 | [access_control_policy.md](../../policies/access_control_policy.md) | ❓ TBC |
| 10.A.6 | Identification | The entity shall periodically, at least annually, review the accounts. This review shall, in particular, verify compliance with these measures relating to identification and, when necessary, correct any anomalies. | 🟠 | [access_control_policy.md](../../policies/access_control_policy.md), [access_review_log.md](../../run/logs/access_review_log.md) | ❓ TBC |
| 14.4 | Crisis management | The entity shall ensure that an up-to-date directory of external stakeholders to the relevant crisis management entity is maintained based on the ecosystem mapping. | 🟠 | [emergency_contacts_register.md](../../run/registers/emergency_contacts_register.md) | ❓ TBC |
| 15.1 | Exercises & drills | The entity shall ensure the awareness and implementation of a tabletop exercise at a defined frequency for people who can be mobilised within the cyber crisis management system. | 🟠 | [business_continuity_plan.md](../../procedures/business_continuity_plan.md) | ❓ TBC |

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
