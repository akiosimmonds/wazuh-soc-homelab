# File integrity monitoring

Wazuh File Integrity Monitoring was configured for **real-time monitoring and file-change reporting** in the Linux homelab.

This provides visibility into changes to monitored filesystem locations. The source record does not list monitored paths, per-endpoint coverage, exclusions, or the exact event metadata. No comprehensive filesystem coverage or attribution capability is implied.

## Evidence to add

- Sanitized FIM configuration identifying the actual monitored locations.
- Representative file-change event and matching Wazuh alert.
- Test context, expected behavior, and any observed limitations.

No sample configuration or generated alert is represented as deployed evidence.

[Back to project](../README.md)
