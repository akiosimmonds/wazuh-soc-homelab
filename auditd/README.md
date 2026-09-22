# Linux auditd integration

Linux `auditd` telemetry was integrated with Wazuh to support security monitoring and custom detection engineering. This telemetry supports [privileged account deletion rule 100003](../detection-engineering/privileged-account-deletion/README.md).

The completed work establishes integration and use of Linux audit telemetry. It does not establish a complete audit policy or coverage of every administrative action.

## Evidence to add

The actual audit configuration, Wazuh collection settings, representative sanitized audit records, and matching alert should be published together. Event types, audit keys, watches, collection paths, and field extraction remain unspecified until those artifacts are available.

[Back to project](../README.md)
