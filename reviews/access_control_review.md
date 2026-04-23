# Access Control Review

## **1. Purpose**
This document records the **quarterly access control review** to ensure that access rights remain appropriate and aligned with organizational policies and **ISO 27001:2022** requirements.

---

## **2. Review Scope**
The review covers:
- All user accounts with access to organizational systems and data.
- Access rights for employees, contractors, and third-party vendors.
- Compliance with the **Access Control Policy** and **MFA Implementation Policy**.

---

## **3. Review Process**
### **3.1 Preparation**
- **Data Collection**: IT Team collects a list of all user accounts and their access rights.
- **Role Mapping**: Managers review and confirm the roles and responsibilities of their team members.

### **3.2 Review**
- **Access Rights**: IT Team reviews access rights to ensure they align with **least privilege** and **RBAC** principles.
- **MFA Compliance**: IT Team verifies that MFA is enabled for all accounts with access to critical systems.
- **Terminated Users**: IT Team confirms that access rights for terminated employees and contractors have been revoked.

### **3.3 Findings**
| **Finding**                          | **Description**                                                                 | **Action Required**                     | **Owner**       | **Timeline**   |
|---------------------------------------|---------------------------------------------------------------------------------|-----------------------------------------|----------------|----------------|
| **MFA Not Enabled for Some Accounts** | 5 accounts with access to critical systems do not have MFA enabled.            | Enable MFA for these accounts.          | IT Team        | 2026-04-15     |
| **Excessive Access Rights**           | 3 employees have access rights beyond their role requirements.                 | Revoke excessive access rights.         | IT Team        | 2026-04-15     |
| **Terminated User Access Not Revoked** | 1 terminated contractor still has active access to organizational systems.     | Revoke access immediately.              | IT Team        | 2026-04-12     |

---

## **4. Review Summary**
- **Total Accounts Reviewed**: 50
- **Accounts with MFA Enabled**: 45 (90%)
- **Accounts with Excessive Access Rights**: 3 (6%)
- **Terminated User Accounts**: 1 (2%)

---

## **5. Next Steps**
- **IT Team**: Address findings by the specified timelines.
- **Managers**: Confirm access rights for their team members.
- **CTO**: Review and approve the access control review report.

---

**Last Updated**: TBD
