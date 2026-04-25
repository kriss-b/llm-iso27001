# Statement of Applicability (SoA)

## 1. Introduction
This **Statement of Applicability (SoA)** identifies the controls from **Annex A of ISO 27001:2022** that are applicable to **ACME CORP** and justifies their inclusion or exclusion. It also tracks the implementation status and the document(s) that implement each control. This document is a key artefact of the **Information Security Management System (ISMS)**.

---

## 2. Scope
This SoA applies to all information assets, systems, and processes within the scope of the ISMS, including:
- Customer data and intellectual property.
- SaaS application code and infrastructure.
- Internal documentation and communication systems.
- Third-party suppliers and vendors.

---

## 3. ISO 27001:2022 Clause Requirements

The following table tracks implementation of the mandatory ISO 27001:2022 clauses (4–10).

| Clause | Requirement | Status | Document |
|--------|-------------|--------|----------|
| 4.1 | Understanding the organization and its context | ❓ TBC | — |
| 4.2 | Understanding the needs and expectations of interested parties | ❓ TBC | — |
| 4.3 | Determining the scope of the ISMS | ❓ TBC | — |
| 4.4 | Information security management system | ❓ TBC | — |
| 5.1 | Leadership and commitment | ❓ TBC | — |
| 5.2 | Policy | ❓ TBC | — |
| 5.3 | Organizational roles, responsibilities and authorities | ❓ TBC | — |
| 6.1 | Actions to address risks and opportunities | ❓ TBC | — |
| 6.2 | Information security objectives and planning to achieve them | ❓ TBC | — |
| 7.1 | Resources | ❓ TBC | — |
| 7.2 | Competence | ❓ TBC | — |
| 7.3 | Awareness | ❓ TBC | — |
| 7.4 | Communication | ❓ TBC | — |
| 7.5 | Documented information | ❓ TBC | — |
| 8.1 | Operational planning and control | ❓ TBC | — |
| 8.2 | Information security risk assessment | ❓ TBC | — |
| 8.3 | Information security risk treatment | ❓ TBC | — |
| 9.1 | Monitoring, measurement, analysis and evaluation | ❓ TBC | — |
| 9.2 | Internal audit | ❓ TBC | — |
| 9.3 | Management review | ❓ TBC | — |
| 10.1 | Nonconformity and corrective action | ❓ TBC | — |
| 10.2 | Continual improvement | ❓ TBC | — |

---

## 4. Annex A Controls

All 93 controls from Annex A are applicable to ACME CORP. Controls not yet implemented are marked ❓ TBC or ❓ TBC.

### A.5 Organisational Controls

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.5.1 | Policies for information security | ❓ TBC | Mandatory for ISMS framework. | [information_security_policy.md](policies/information_security_policy.md) |
| A.5.2 | Information security roles and responsibilities | ❓ TBC | Ensures accountability across the organisation. | [roles_and_responsibilities_policy.md](policies/roles_and_responsibilities_policy.md) |
| A.5.3 | Segregation of duties | ❓ TBC | Prevents single points of failure or fraud. | [roles_and_responsibilities_policy.md](policies/roles_and_responsibilities_policy.md) |
| A.5.4 | Management responsibilities | ❓ TBC | Leadership commitment is required for ISMS effectiveness. | [roles_and_responsibilities_policy.md](policies/roles_and_responsibilities_policy.md) |
| A.5.5 | Contact with authorities | ❓ TBC | Required for regulatory compliance and incident reporting. | [isms_policy.md](policies/isms_policy.md) |
| A.5.6 | Contact with special interest groups | ❓ TBC | Ensures awareness of emerging threats and best practices. | [isms_policy.md](policies/isms_policy.md) |
| A.5.7 | Threat intelligence | ❓ TBC | Critical for identifying and mitigating threats proactively. | [risk_assessment_framework.md](risk_assessment/risk_assessment_framework.md) |
| A.5.8 | Information security in project management | ❓ TBC | Ensures security is integrated into all projects from the start. | — |
| A.5.9 | Inventory of information and other associated assets | ❓ TBC | Required for asset management and risk assessment. | [asset_management_policy.md](policies/asset_management_policy.md) |
| A.5.10 | Acceptable use of information and other associated assets | ❓ TBC | Defines acceptable behaviour for all users. | [acceptable_use_policy.md](policies/acceptable_use_policy.md) |
| A.5.11 | Return of assets | ❓ TBC | Ensures secure return or disposal of assets on departure. | [disposal_destruction_policy.md](policies/disposal_destruction_policy.md) |
| A.5.12 | Classification of information | ❓ TBC | Required for appropriate handling and protection of data. | [data_classification_policy.md](policies/data_classification_policy.md) |
| A.5.13 | Labelling of information | ❓ TBC | Ensures classified information is consistently identified. | [data_classification_policy.md](policies/data_classification_policy.md) |
| A.5.14 | Information transfer | ❓ TBC | Ensures secure transfer of data internally and externally. | [communication_security_policy.md](policies/communication_security_policy.md) |
| A.5.15 | Access control | ❓ TBC | Critical for protecting systems and data from unauthorised access. | [access_control_policy.md](policies/access_control_policy.md) |
| A.5.16 | Identity management | ❓ TBC | Ensures unique identification and lifecycle management of users. | [access_control_policy.md](policies/access_control_policy.md) |
| A.5.17 | Authentication information | ❓ TBC | Protects passwords and credentials. | [access_control_policy.md](policies/access_control_policy.md) |
| A.5.18 | Access rights | ❓ TBC | Ensures least privilege and regular access reviews. | [access_control_policy.md](policies/access_control_policy.md) |
| A.5.19 | Information security in supplier relationships | ❓ TBC | Manages third-party security risks. | [supplier_security_policy.md](policies/supplier_security_policy.md) |
| A.5.20 | Addressing information security within supplier agreements | ❓ TBC | Ensures contractual security requirements are met. | [supplier_security_policy.md](policies/supplier_security_policy.md) |
| A.5.21 | Managing information security in the ICT supply chain | ❓ TBC | Ensures security across the full supply chain. | [supplier_security_policy.md](policies/supplier_security_policy.md) |
| A.5.22 | Monitoring, review and change management of supplier services | ❓ TBC | Ensures ongoing compliance of suppliers. | [supplier_security_policy.md](policies/supplier_security_policy.md) |
| A.5.23 | Information security for use of cloud services | ❓ TBC | Critical for a SaaS business relying on cloud infrastructure. | [cloud_security_policy.md](policies/cloud_security_policy.md) |
| A.5.24 | Information security incident management planning and preparation | ❓ TBC | Ensures readiness to detect and respond to incidents. | [incident_management_policy.md](policies/incident_management_policy.md) |
| A.5.25 | Assessment and decision on information security events | ❓ TBC | Ensures timely and consistent triage of security events. | [incident_response_plan.md](incident_management/incident_response_plan.md) |
| A.5.26 | Response to information security incidents | ❓ TBC | Defines structured response to security incidents. | [incident_response_plan.md](incident_management/incident_response_plan.md) |
| A.5.27 | Learning from information security incidents | ❓ TBC | Ensures continuous improvement from incident lessons learned. | [incident_response_plan.md](incident_management/incident_response_plan.md) |
| A.5.28 | Collection of evidence | ❓ TBC | Required for legal and regulatory proceedings. | [incident_response_plan.md](incident_management/incident_response_plan.md) |
| A.5.29 | Information security during disruption | ❓ TBC | Ensures business continuity during security incidents. | [business_continuity_policy.md](policies/business_continuity_policy.md) |
| A.5.30 | ICT readiness for business continuity | ❓ TBC | Ensures IT resilience and recovery capability. | [business_continuity_plan.md](procedures/business_continuity_plan.md), [disaster_recovery_plan.md](procedures/disaster_recovery_plan.md) |
| A.5.31 | Legal, statutory, regulatory and contractual requirements | ❓ TBC | Ensures compliance with applicable laws and regulations. | [compliance_policy.md](policies/compliance_policy.md) |
| A.5.32 | Intellectual property rights | ❓ TBC | Protects company and customer intellectual property. | [compliance_policy.md](policies/compliance_policy.md) |
| A.5.33 | Protection of records | ❓ TBC | Ensures integrity and availability of records. | [data_retention_disposal_policy.md](policies/data_retention_disposal_policy.md) |
| A.5.34 | Privacy and protection of PII | ❓ TBC | Required for GDPR compliance. | [data_protection_policy.md](policies/data_protection_policy.md) |
| A.5.35 | Independent review of information security | ❓ TBC | Ensures objectivity in ISMS reviews and audit findings. | [audit_policy.md](policies/audit_policy.md) |
| A.5.36 | Compliance with policies, rules and standards | ❓ TBC | Ensures adherence to internal policies and external standards. | [compliance_policy.md](policies/compliance_policy.md) |
| A.5.37 | Documented operating procedures | ❓ TBC | Ensures consistency and repeatability of operations. | [procedures/](procedures/) |

### A.6 People Controls

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.6.1 | Screening | ❓ TBC | Reduces risk from insider threats during hiring. | [human_resource_security_policy.md](policies/human_resource_security_policy.md) |
| A.6.2 | Terms and conditions of employment | ❓ TBC | Establishes security obligations for all staff. | [human_resource_security_policy.md](policies/human_resource_security_policy.md) |
| A.6.3 | Information security awareness, education and training | ❓ TBC | Ensures staff can recognise and respond to security threats. | [employee_training_procedure.md](procedures/employee_training_procedure.md) |
| A.6.4 | Disciplinary process | ❓ TBC | Enforces accountability for security policy violations. | [human_resource_security_policy.md](policies/human_resource_security_policy.md) |
| A.6.5 | Responsibilities after termination or change of employment | ❓ TBC | Ensures security obligations survive employment changes. | [human_resource_security_policy.md](policies/human_resource_security_policy.md) |
| A.6.6 | Confidentiality or non-disclosure agreements | ❓ TBC | Required to protect sensitive information shared with staff and third parties. | [confidentiality_agreement_template.md](procedures/confidentiality_agreement_template.md) |
| A.6.7 | Remote working | ❓ TBC | Addresses security risks of working outside office premises. | [mobile_device_policy.md](policies/mobile_device_policy.md) |
| A.6.8 | Information security event reporting | ❓ TBC | Ensures timely reporting of security events by all staff. | [incident_management_policy.md](policies/incident_management_policy.md) |

### A.7 Physical Controls

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.7.1 | Physical security perimeters | ❓ TBC | Protects facilities from unauthorised physical access. | [physical_and_environmental_security_policy.md](policies/physical_and_environmental_security_policy.md) |
| A.7.2 | Physical entry | ❓ TBC | Controls and logs access to secure areas. | [physical_and_environmental_security_policy.md](policies/physical_and_environmental_security_policy.md) |
| A.7.3 | Securing offices, rooms and facilities | ❓ TBC | Protects sensitive areas from unauthorised access. | [physical_and_environmental_security_policy.md](policies/physical_and_environmental_security_policy.md) |
| A.7.4 | Physical security monitoring | ❓ TBC | Detects and deters physical security incidents. | [physical_and_environmental_security_policy.md](policies/physical_and_environmental_security_policy.md) |
| A.7.5 | Protecting against physical and environmental threats | ❓ TBC | Mitigates risks from natural and environmental hazards. | [physical_and_environmental_security_policy.md](policies/physical_and_environmental_security_policy.md), [environmental_risk_assessment.md](risk_assessment/environmental_risk_assessment.md) |
| A.7.6 | Working in secure areas | ❓ TBC | Prevents unauthorised observation or interference in sensitive areas. | [physical_and_environmental_security_policy.md](policies/physical_and_environmental_security_policy.md) |
| A.7.7 | Clear desk and clear screen | ❓ TBC | Prevents unauthorised access to information left unattended. | [clear_desk_policy.md](policies/clear_desk_policy.md) |
| A.7.8 | Equipment siting and protection | ❓ TBC | Protects equipment from physical damage and theft. | [physical_and_environmental_security_policy.md](policies/physical_and_environmental_security_policy.md) |
| A.7.9 | Security of assets off-premises | ❓ TBC | Addresses risks when assets are used outside company premises. | [mobile_device_policy.md](policies/mobile_device_policy.md) |
| A.7.10 | Storage media | ❓ TBC | Ensures secure handling and disposal of storage media. | [data_retention_disposal_policy.md](policies/data_retention_disposal_policy.md), [disposal_destruction_policy.md](policies/disposal_destruction_policy.md) |
| A.7.11 | Supporting utilities | ❓ TBC | Ensures availability of power, cooling and other utilities for critical systems. | — |
| A.7.12 | Cabling security | ❓ TBC | Protects network and power cabling from interference or damage. | — |
| A.7.13 | Equipment maintenance | ❓ TBC | Ensures continued availability and integrity of equipment. | — |
| A.7.14 | Secure disposal or re-use of equipment | ❓ TBC | Prevents data leakage from disposed or repurposed equipment. | [disposal_destruction_policy.md](policies/disposal_destruction_policy.md) |

### A.8 Technological Controls

| Control | Title | Status | Justification | Document |
|---------|-------|--------|---------------|----------|
| A.8.1 | User endpoint devices | ❓ TBC | Secures laptops, mobile devices and other endpoints. | [mobile_device_policy.md](policies/mobile_device_policy.md) |
| A.8.2 | Privileged access rights | ❓ TBC | Limits and controls administrative access to critical systems. | [access_control_policy.md](policies/access_control_policy.md) |
| A.8.3 | Information access restriction | ❓ TBC | Ensures users access only information they are authorised to see. | [access_control_policy.md](policies/access_control_policy.md) |
| A.8.4 | Access to source code | ❓ TBC | Protects source code from unauthorised access or modification. | [secure_development_policy.md](policies/secure_development_policy.md) |
| A.8.5 | Secure authentication | ❓ TBC | Ensures strong authentication mechanisms are in place. | [access_control_policy.md](policies/access_control_policy.md) |
| A.8.6 | Capacity management | ❓ TBC | Ensures adequate capacity to meet performance requirements. | — |
| A.8.7 | Protection against malware | ❓ TBC | Detects and prevents malware on all endpoints and servers. | [operations_security_policy.md](policies/operations_security_policy.md) |
| A.8.8 | Management of technical vulnerabilities | ❓ TBC | Reduces attack surface through timely patching and vulnerability tracking. | [operations_security_policy.md](policies/operations_security_policy.md), [patch_management_procedure.md](procedures/patch_management_procedure.md) |
| A.8.9 | Configuration management | ❓ TBC | Ensures systems are configured securely and consistently. | — |
| A.8.10 | Information deletion | ❓ TBC | Ensures data is securely deleted when no longer required. | [data_retention_disposal_policy.md](policies/data_retention_disposal_policy.md), [disposal_destruction_policy.md](policies/disposal_destruction_policy.md) |
| A.8.11 | Data masking | ❓ TBC | Protects sensitive data in non-production environments. | — |
| A.8.12 | Data leakage prevention | ❓ TBC | Prevents unauthorised exfiltration of sensitive data. | — |
| A.8.13 | Information backup | ❓ TBC | Ensures data can be recovered after loss or corruption. | [backup_procedure.md](procedures/backup_procedure.md) |
| A.8.14 | Redundancy of information processing facilities | ❓ TBC | Ensures availability of critical IT systems. | [disaster_recovery_plan.md](procedures/disaster_recovery_plan.md) |
| A.8.15 | Logging | ❓ TBC | Enables detection of and response to security events. | [operations_security_policy.md](policies/operations_security_policy.md) |
| A.8.16 | Monitoring activities | ❓ TBC | Detects anomalies and suspicious behaviour in real time. | [operations_security_policy.md](policies/operations_security_policy.md) |
| A.8.17 | Clock synchronisation | ❓ TBC | Ensures consistent and reliable timestamps across systems for log correlation. | [operations_security_policy.md](policies/operations_security_policy.md) |
| A.8.18 | Use of privileged utility programs | ❓ TBC | Controls use of tools that could bypass security controls. | — |
| A.8.19 | Installation of software on operational systems | ❓ TBC | Prevents unauthorised or untested software from being deployed. | [operations_security_policy.md](policies/operations_security_policy.md) |
| A.8.20 | Networks security | ❓ TBC | Protects the network infrastructure from attack and misuse. | [communication_security_policy.md](policies/communication_security_policy.md) |
| A.8.21 | Security of network services | ❓ TBC | Ensures network services are secured and monitored. | [communication_security_policy.md](policies/communication_security_policy.md) |
| A.8.22 | Segregation of networks | ❓ TBC | Limits the impact of a breach by isolating network segments. | [communication_security_policy.md](policies/communication_security_policy.md) |
| A.8.23 | Web filtering | ❓ TBC | Blocks access to malicious or unauthorised web content. | [communication_security_policy.md](policies/communication_security_policy.md) |
| A.8.24 | Use of cryptography | ❓ TBC | Protects confidentiality and integrity of data in transit and at rest. | [cryptography_policy.md](policies/cryptography_policy.md) |
| A.8.25 | Secure development life cycle | ❓ TBC | Integrates security into the full software development lifecycle. | [secure_development_policy.md](policies/secure_development_policy.md) |
| A.8.26 | Application security requirements | ❓ TBC | Ensures security is defined as a requirement for all applications. | [secure_development_policy.md](policies/secure_development_policy.md) |
| A.8.27 | Secure system architecture and engineering principles | ❓ TBC | Ensures systems are designed with security by default. | [secure_development_policy.md](policies/secure_development_policy.md) |
| A.8.28 | Secure coding | ❓ TBC | Reduces vulnerabilities introduced during development. | [secure_development_policy.md](policies/secure_development_policy.md) |
| A.8.29 | Security testing in development and acceptance | ❓ TBC | Validates security controls before systems go live. | [secure_development_policy.md](policies/secure_development_policy.md) |
| A.8.30 | Outsourced development | ❓ TBC | Ensures third-party developers meet security requirements. | [secure_development_policy.md](policies/secure_development_policy.md), [system_acquisition_development_and_maintenance_policy.md](policies/system_acquisition_development_and_maintenance_policy.md) |
| A.8.31 | Separation of development, test and production environments | ❓ TBC | Prevents accidental exposure of production data during testing. | [secure_development_policy.md](policies/secure_development_policy.md) |
| A.8.32 | Change management | ❓ TBC | Controls changes to systems to prevent unintended security impacts. | [change_management_policy.md](policies/change_management_policy.md) |
| A.8.33 | Test information | ❓ TBC | Ensures test data does not include real sensitive data. | [secure_development_policy.md](policies/secure_development_policy.md) |
| A.8.34 | Protection of information systems during audit testing | ❓ TBC | Prevents audit activities from disrupting or compromising production systems. | [audit_policy.md](policies/audit_policy.md) |

---

## 5. Review and Updates
This SoA will be reviewed **annually** or after significant changes to the ISMS or business environment.

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | ISMS Owner | CEO | Initial version |
| 1.1 | TBD | ISMS Owner | CEO | Merged checklist into SoA: added Document column, clause requirements table, corrected stale statuses |
