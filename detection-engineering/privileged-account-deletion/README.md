# Privileged Linux account deletion

| Field | Recorded implementation |
| --- | --- |
| Wazuh rule ID | **100003** |
| Use case | Privileged Linux account deletion |
| Telemetry | Linux auditd integrated with Wazuh |
| ATT&CK mapping | **T1531 — Account Access Removal** |
| Validation | Developed and validated through controlled activity; tuning addressed duplicate alerts |

The mapping expresses the detection's intended behavior. An alert alone does not prove malicious intent; account removal can be authorized administrative activity.

## What remains to be documented

The actual rule XML, audit event types, audit keys, field matches, definition of privileged account, and duplicate-alert mechanism are not available in the project record. No UID threshold, command match, audit watch, rule severity, or suppression logic is invented here.

To make the case study independently reviewable, add the sanitized deployed rule, representative audit records, matching alert with T1531, and the actual before/after tuning explanation. No numerical improvement is claimed.

[auditd integration](../../auditd/README.md) · [Detection index](../README.md)
