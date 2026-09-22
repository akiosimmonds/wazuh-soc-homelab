# Architecture

## Confirmed components

| Component | Confirmed role |
| --- | --- |
| Wazuh SIEM | Central security monitoring, custom detection, response, vulnerability findings, and SCA |
| CyberLab | Ubuntu virtual machine monitored by Wazuh |
| CyberPi | Physical Raspberry Pi 5 running Debian 13, monitored by Wazuh |
| Linux auditd | Audit telemetry integrated with Wazuh |
| Wazuh FIM | Real-time file monitoring and file-change reporting |
| Pi-hole | DNS filtering used by multiple endpoints |
| Tailscale | Secure remote connectivity |

## Logical flow

Monitored Linux endpoints provide telemetry to Wazuh. Custom detection work includes SSH authentication correlation and privileged account deletion using Linux audit telemetry. The SSH detection is associated with Active Response block/unblock behavior.

The root README diagram represents these logical relationships only. It intentionally omits unverified network links and deployment details.

## Details awaiting sanitized evidence

- Wazuh version, server host, and placement of its components.
- Actual network boundaries and endpoint addressing scheme.
- Where Pi-hole and Tailscale run and how access is restricted.
- Per-endpoint FIM/auditd coverage and event collection configuration.
- Active Response execution location and response duration.

No IP addresses, ports, VM resource allocations, firewall rules, or network segmentation are inferred here.

[Back to project](../README.md)
