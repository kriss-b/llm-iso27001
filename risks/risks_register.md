# ISO 27001:2022 Risk Register

## **1. Introduction**
This **Risk Register** documents identified risks, their assessment, and treatment plans. It is maintained in accordance with the **[Risk Assessment Procedure](risk_assessment_procedure.md)** and **ISO 27001:2022** requirements.

The risks listed below are **examples** provided as a starting point. Replace them with risks identified during your organisation's own risk assessment.

---

## **2. Risk Register**
| **Risk ID** | **Risk Description** | **Threat** | **Weakness** | **Likelihood** | **Impact** | **Risk Level** | **Treatment option** | **Treatment controls** | **Treatment rationale** | **Residual Risk** | **Owner** | **Status** | **AI Specificity** |
|-------------|----------------------|------------|--------------|----------------|------------|----------------|----------------------|------------------------|-------------------------|-------------------|-----------|------------|-------------------|
| RISK-EXAMPLE-001 | Unauthorized access to customer data | Cyberattack | Weak access controls | High | High | High | Mitigate | A.5.15, A.5.18, A.8.5 | — | TBD | CTO | In Progress | Indirect |
| RISK-EXAMPLE-002 | Data breach due to unpatched software | Cyberattack | Lack of patch management | Medium | High | High | Mitigate | A.8.8, A.8.32 | — | TBD | John Smith | To Do | Indirect |
| RISK-EXAMPLE-004 | Phishing attacks leading to credential theft | Social engineering | Lack of employee training | High | Medium | High | Mitigate | A.6.3, A.8.5 | — | TBD | Jane Doe | To Do | Indirect |
| RISK-EXAMPLE-005 | Non-compliance with ISO 27001 requirements | Regulatory change | Lack of documentation | Medium | High | High | Mitigate | A.5.1, A.5.35, A.5.36 | — | TBD | ISMS Owner | In Progress | None |
| RISK-EXAMPLE-006 | Third-party vendor security breach | Third-party compromise | Inadequate vendor security review | Medium | High | High | Mitigate | A.5.19, A.5.20, A.5.22 | — | TBD | COO | To Do | Indirect |
| RISK-EXAMPLE-007 | Insider threat (malicious or accidental) | Employee misconduct | Lack of monitoring | Medium | High | High | Mitigate | A.6.4, A.8.15, A.8.16 | — | TBD | Alex Johnson | To Do | Indirect |
| RISK-EXAMPLE-009 | Environmental changes (e.g., floods, fires) disrupt SaaS operations | Natural disaster | No environmental risk assessment | Medium | High | High | Accept | — | No owned data centres; continuity obligations sit with the cloud provider under contract. Accepted by the ISMS Owner. | High | COO | Done | None |
| RISK-EXAMPLE-010 | Supply chain attack via third-party dependencies | Cyberattack | Lack of supply chain security controls | Medium | High | High | Mitigate | A.5.21, A.8.8, A.8.28 | — | TBD | CTO | To Do | Indirect |
| RISK-EXAMPLE-011 | AI system generates false or misleading output acted upon by users or automated processes | Unreliable AI output | Lack of output validation and human oversight mechanisms | High | High | High | Mitigate | 42001:A.6.2.4, 42001:A.6.2.6, 42001:A.9.2 | — | TBD | Jane Doe | To Do | Direct |
| RISK-EXAMPLE-012 | Malicious manipulation of LLM inputs to bypass controls, extract sensitive data, or trigger unintended actions | Adversarial input | Lack of prompt sanitization and input security controls | Medium | High | High | Mitigate | A.8.26, A.8.28, 42001:A.6.2.4 | — | TBD | CTO | To Do | Direct |

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | ISMS Owner | ISMS Owner | Initial version |
