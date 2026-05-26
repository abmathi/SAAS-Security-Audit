# Security Incident Report

**Framework Alignment**
- SOC 2
- NIST CSF 2.0

## Incident Summary
Multiple failed authentication attempts followed by a successful login were identified on a privileged GitHub account.

## Incident Classification
Medium Severity – Suspicious Authentication Activity

## Detection Method
Security log review and authentication monitoring.

## Timeline
- Failed login attempts observed
- Successful authentication event identified
- Session activity reviewed
- MFA status verified
- Active sessions reviewed and validated

## Potential Impact
Unauthorized account access could result in:
- Source code exposure
- Repository tampering
- Credential compromise
- Supply chain risk

## Response Actions
- Reviewed active sessions
- Validated MFA enforcement
- Reviewed account activity
- Confirmed no unauthorized repository changes identified

## Lessons Learned
- Improve login alerting visibility
- Enable centralized monitoring
- Perform periodic privileged account reviews

## Evidence Screenshots

### Incident Report Documentation

![Incident Report](../screenshots/step-08-incident-report.png)

### Incident Tracking Spreadsheet

![Incident Tracking](../screenshots/step-08-incident-tracking.png)

### Security Log Evidence

![Incident Log Evidence](../screenshots/step-08-incident-log-evidence.png)

## Recommendations
- Configure automated suspicious login alerts
- Expand SIEM monitoring coverage
- Conduct periodic incident response tabletop exercises