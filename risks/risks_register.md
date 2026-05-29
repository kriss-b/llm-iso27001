# ISO 27001:2022 Risk Register

## **1. Introduction**
This **Risk Register** documents identified risks, their assessment, and treatment plans. It is maintained in accordance with the **[Risk Assessment Framework](risk_assessment_framework.md)** and **ISO 27001:2022** requirements.

The risks listed below are **examples** provided as a starting point. Replace them with risks identified during your organisation's own risk assessment.

---

## **2. Risk Register**
| **Risk ID** | **Risk Description** | **Threat** | **Weakness** | **Likelihood** | **Impact** | **Risk Level** | **Treatment** | **Residual Risk** | **Owner** | **Status** | **AI Specificity** |
|-------------|----------------------|------------|--------------|----------------|------------|----------------|---------------|-------------------|-----------|------------|-------------------|
| RISK-EXAMPLE-001 | Unauthorized access to customer data | Cyberattack | Weak access controls | High | High | High | Implement MFA and RBAC | TBD | CTO | In Progress | Indirect |
| RISK-EXAMPLE-002 | Data breach due to unpatched software | Cyberattack | Lack of patch management | Medium | High | High | Automate patch management | TBD | John Smith | To Do | Indirect |
| RISK-EXAMPLE-004 | Phishing attacks leading to credential theft | Social engineering | Lack of employee training | High | Medium | High | Conduct security awareness training | TBD | Jane Doe | To Do | Indirect |
| RISK-EXAMPLE-005 | Non-compliance with ISO 27001 requirements | Regulatory change | Lack of documentation | Medium | High | High | Develop and maintain ISMS documentation | TBD | ISMS Owner | In Progress | None |
| RISK-EXAMPLE-006 | Third-party vendor security breach | Third-party compromise | Inadequate vendor security review | Medium | High | High | Review and update vendor contracts | TBD | COO | To Do | Indirect |
| RISK-EXAMPLE-007 | Insider threat (malicious or accidental) | Employee misconduct | Lack of monitoring | Medium | High | High | Implement logging and monitoring | TBD | Alex Johnson | To Do | Indirect |
| RISK-EXAMPLE-009 | Environmental changes (e.g., floods, fires) disrupt SaaS operations | Natural disaster | No environmental risk assessment | Medium | High | High | Conduct environmental risk assessment and document mitigation strategies | TBD | COO | To Do | None |
| RISK-EXAMPLE-010 | Supply chain attack via third-party dependencies | Cyberattack | Lack of supply chain security controls | Medium | High | High | Implement supply chain security controls (e.g., dependency scanning, vendor security reviews) | TBD | CTO | To Do | Indirect |
| RISK-EXAMPLE-011 | AI system generates false or misleading output acted upon by users or automated processes | Unreliable AI output | Lack of output validation and human oversight mechanisms | High | High | High | Implement output validation, human-in-the-loop review for high-stakes decisions, hallucination detection | TBD | Jane Doe | To Do | Direct |
| RISK-EXAMPLE-012 | Malicious manipulation of LLM inputs to bypass controls, extract sensitive data, or trigger unintended actions | Adversarial input | Lack of prompt sanitization and input security controls | Medium | High | High | Implement prompt sanitization, input validation, output filtering, privilege separation between system and user prompts | TBD | CTO | To Do | Direct |

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | ISMS Owner | ISMS Owner | Initial version |
