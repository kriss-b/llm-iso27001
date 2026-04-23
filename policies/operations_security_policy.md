# Operations Security Policy

## 1. Purpose
This policy ensures the secure operation of information systems and processes in alignment with **ISO 27001:2022 (Controls A.8.7, A.8.8, A.8.13, A.8.15, A.8.16, A.8.17 and A.8.19)**, which cover protection against malware, vulnerability management, backups, logging, monitoring, clock synchronisation, and software installation.

## 2. Scope
This policy applies to all employees, contractors, and third parties responsible for the operation and maintenance of the Company’s information systems.

## 3. Policy Statements
### 3.1 Change Management
- All changes to information systems must be documented, tested, and approved before implementation.
- Emergency changes must be reviewed and approved retrospectively.

### 3.2 Backup and Recovery
- Critical data must be backed up daily and tested quarterly.
- Backup media must be stored securely and encrypted.

### 3.3 Logging and Monitoring
- System logs must be enabled for all critical systems and retained for at least 90 days.
- Logs must be monitored for suspicious activity (e.g., failed login attempts, unauthorized access).

### 3.4 Malware Protection
- Anti-malware software must be installed and updated on all endpoints and servers.
- Regular scans must be conducted to detect and remove malware.

### 3.5 Clock Synchronisation
- All servers, network devices, and critical systems must synchronise their clocks using a reliable time source (e.g., NTP servers).
- A consistent and authoritative time source must be configured across all environments (development, staging, production).
- Clock synchronisation must be monitored; significant drift must be alerted and corrected promptly.
- Accurate timestamps are essential for log integrity, incident investigation, and audit trail reliability.

### 3.6 Patch Management
- Security patches must be applied within 30 days of release for critical systems.
- End-of-life software must not be used in production.

## 4. Roles and Responsibilities
### 4.1 CTO (Owner)
- Implement and maintain operational security controls.

### 4.2 IT Team
- Support the CTO in implementing operational security controls.

### 4.3 Developers
- Ensure secure coding practices and patch management.

### 4.4 Employees
- Comply with operational security procedures.

## 5. Compliance
Non-compliance with this policy may result in disciplinary action, up to and including termination of employment or contracts.

## 6. Review and Updates
This policy will be reviewed annually or after significant changes to operations or threats.


---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | CTO | ISMS Owner | Initial version |
| 1.1 | TBD | CTO | ISMS Owner | Add clock synchronisation section (A.8.17) |
