# ISO 27001:2022 Risk Assessment Framework

## **1. Purpose**
This framework outlines the methodology for identifying, assessing, and treating information security risks in accordance with **ISO 27001:2022**. It ensures that risks are managed systematically to protect the confidentiality, integrity, and availability of information assets.

---

## **2. Scope**
This framework applies to:
- All information assets owned or managed by the organization.
- All employees, contractors, and third-party vendors with access to organizational information.
- All processes, systems, and technologies used to store, process, or transmit information.

---

## **3. Risk Assessment Methodology**

### **3.0 Risk Criteria**
Risk criteria shall be established before each risk assessment and documented in the Risk Assessment Report. They define the scales used to assess likelihood and impact, and the threshold above which risks require treatment.

**Likelihood:**

| Level | Definition |
|---|---|
| **High** | Can occur approximately once per year, or has already occurred |
| **Medium** | Can occur approximately once every 5 years |
| **Low** | Can occur approximately once every 10 years |

**Impact** (highest applicable dimension drives the level):

| Level | Definition |
|---|---|
| **High** | Service disruption > 48h; OR confirmed personal data breach; OR regulatory fine likely; OR major reputational damage |
| **Medium** | Service disruption between 4h and 48h; OR potential data exposure of limited scope; OR regulatory attention possible; OR contained reputational impact |
| **Low** | Service disruption < 4h; no personal data at risk; no regulatory implications; negligible reputational impact |

**Risk acceptance threshold:**

| Risk Level | Decision |
|---|---|
| **Low** | Acceptable — log and monitor |
| **Medium** | Management review required; may be accepted with documented justification |
| **High** | Treatment required; acceptance only with explicit CEO or ISMS Owner sign-off |

### **3.1 Risk Identification**
- **Assets**: Identify all information assets (e.g., data, systems, hardware, software, people).
- **Threats**: Identify potential threats (e.g., cyberattacks, human error, natural disasters).
- **Vulnerabilities**: Identify weaknesses that could be exploited by threats (e.g., unpatched software, lack of MFA).
- **Impacts**: Determine the potential impact of a security incident (e.g., financial loss, reputational damage, legal consequences).
- **AI Specificity**: Classify each risk according to how directly it relates to AI systems, using one of three values:
  - `None`: The risk has no meaningful connection to AI systems or their use.
  - `Indirect`: The risk originates independently of AI but also applies to AI systems (e.g., unauthorized access, supply chain attack).
  - `Direct`: The risk only exists because of AI systems (e.g., model poisoning, hallucination, prompt injection, training data leakage).

### **3.2 Risk Analysis**
- **Likelihood**: Assess the likelihood of a risk occurring (e.g., Low, Medium, High).
- **Impact**: Assess the impact of a risk if it occurs (e.g., Low, Medium, High).
- **Risk Level**: Calculate the risk level using a **Risk Matrix** (see Section 5).

### **3.3 Risk Evaluation**
- Compare the risk level against the organization’s **risk appetite**.
- Determine whether the risk is **acceptable** or requires **treatment**.

### **3.4 Risk Treatment**
- **Options**: 
  - **Mitigate**: Implement controls to reduce the risk.
  - **Accept**: Accept the risk if it is within the risk appetite.
  - **Avoid**: Eliminate the risk by discontinuing the activity.
  - **Transfer**: Transfer the risk (e.g., via insurance or outsourcing).
- **Controls**: Select controls from **Annex A of ISO 27001:2022** to mitigate risks.

---

## **4. Roles and Responsibilities**
| **Role**               | **Responsibility**                                                                 |
|------------------------|------------------------------------------------------------------------------------|
| **ISMS Owner**         | Oversees the risk assessment process and ensures compliance with ISO 27001.        |
| **Risk Assessment Team** | Identifies, analyzes, and evaluates risks.                                        |
| **IT Team**            | Provides technical input on vulnerabilities and controls.                          |
| **Management**         | Approves risk treatment plans and provides resources for mitigation.               |
| **Employees**          | Report risks and adhere to risk treatment measures.                               |

---

## **5. Risk Matrix**
| **Likelihood \ Impact** | **Low** | **Medium** | **High** |
|-----------------------|---------|------------|---------|
| **Low**               | Low     | Low        | Medium  |
| **Medium**            | Low     | Medium     | High    |
| **High**              | Medium  | High       | High    |

---

## **6. Risk Assessment Frequency**
- **Annual Review**: Conduct a full risk assessment annually.
- **Ad-Hoc Review**: Conduct a risk assessment after significant changes (e.g., new systems, mergers, cyber incidents).

---

## **7. Documentation**
- **[Risk Register](risks_register.md)**: Document all identified risks, their assessment, and treatment plans.
- **Risk findings and recommendations** are presented at the annual management review using the **[Management Review Template](../procedures/management_review_template.md)** (§11 and §12).

---

## **8. Review and Improvement**
- This framework will be reviewed annually or after significant changes to ensure its effectiveness.
- Feedback from risk assessments will be used to improve the framework.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | ISMS Owner | ISMS Owner | Initial version |
