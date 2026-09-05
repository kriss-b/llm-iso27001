# Incident Report — INC-EXAMPLE-001

**Incident ID**: INC-EXAMPLE-001
**Date of Report**: 2026-09-03
**Reported by**: Platform Engineer
**Contact**: security@acme.example

> Worked example. Completed instance of [incident_report_template.md](../../../incidents/incident_report_template.md), indexed from [incidents_log.md](../../../incidents/incidents_log.md).

---

## 1. Incident Details
**Date/Time of Incident**: 2026-09-03 09:12
**Detection Method**: Automated alert (API error rate)
**Severity**: Low
**AI Specificity**: None

### 1.1 Description
Login API returned errors for 6 minutes after a configuration change. Customers could not sign in.

### 1.2 Impact
- **Confidentiality**: None.
- **Integrity**: None.
- **Availability**: 6 minutes, login only. Within the recovery objective.
- **Regulatory**: None.

---

## 2. Response Actions
### 2.1 Containment
Change rolled back at 09:18.

### 2.2 Eradication
Not applicable — no threat.

### 2.3 Recovery
Error rate normal at 09:19. No data loss.

---

## 3. Root Cause Analysis
Connection pool limit lowered by a config change; not caught in staging, which runs at lower load.

---

## 4. Lessons Learned
- Load-test config changes before release — ACT-EXAMPLE-014 in the [Action Register](../../registers/actions_register.md).

---

## 5. Approvals
**Incident Response Manager**: *signed* [CISO, 2026-09-03]
**IT Manager**: *signed* [IT Manager, 2026-09-03]
