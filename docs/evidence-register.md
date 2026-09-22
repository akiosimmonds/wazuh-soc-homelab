# Evidence register

## Provenance and limits

This initial repository is based on the owner's completed-work inventory in **Cybersecurity Portfolio Development**, reaffirmed in the repository creation request. It records reported implementation and validation; it is not an independent re-test of the running environment.

No raw lab logs, rule/configuration exports, scan reports, or lab screenshots were available for this publication. The repository therefore contains narrative documentation and a logical architecture diagram only. Suggested evidence below is **pending**, not attached.

| Claim | Recorded status | Supporting artifact still to add |
| --- | --- | --- |
| Wazuh with CyberLab and CyberPi | Completed | Sanitized agent inventory and architecture details |
| Five invalid SSH attempts within 60 seconds | Developed and tested | Actual rule and timestamped event sequence |
| firewall-drop block/unblock | Implemented and tested | Trigger configuration and both response records |
| Rule 100003 / T1531 | Developed and validated | Rule XML, audit event, matching alert |
| Controlled testing and tuning | Completed; duplicate alerts addressed | Actual test notes and rule changes |
| Real-time FIM | Configured | Actual monitored-path configuration and event |
| auditd integration | Completed | Collection configuration and matching telemetry |
| Contextual CVE triage | Performed | Real finding and documented decision |
| SSH/UFW and other Linux hardening | Implemented | Sanitized effective configuration |
| Pi-hole | Deployed; multiple endpoints integrated | Service and client DNS validation |
| Tailscale | Implemented | Sanitized connectivity evidence |
| CIS Debian 13 SCA | 41% baseline; at least 52% interim | Comparable assessment reports and policy details |
| CIS exceptions/scanner mismatches | Evaluated | Actual check-specific rationale and evidence |
| Infrastructure troubleshooting | Performed | Specific symptoms, diagnosis, changes, validation |

## Evidence maintenance

When adding an artifact, record its capture date, scope, relevant configuration/version, what it supports, and any limitations. An artifact supports only the behavior it shows; a single successful test does not establish broad detection coverage or ongoing reliability.

[Back to project](../README.md)
