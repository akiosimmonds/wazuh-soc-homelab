# CIS Debian 13 hardening — in progress

| Stage | Reported Wazuh SCA result |
| --- | --- |
| Initial CyberPi baseline | **41%** |
| Subsequent hardening progress | **At least 52%** |
| Final assessment | Not completed |

These figures come from the completed-work inventory. Scan exports, assessment dates, policy revisions, and check totals are not yet included. They should not be read as a certified compliance result or a measure of total system security.

## Completed remediation areas

Work addressed unnecessary services, SSH controls, cron permissions, login banners, and other Linux configuration findings. The precise CIS check IDs and configuration changes must be recorded from real artifacts.

## Risk-based decisions

CIS findings were assessed using risk-based decisions, including accepted exceptions and architecture-specific scanner mismatches. A failed scanner check is not automatically a valid exception; the justification needs evidence specific to the system and check.

No individual exception is reconstructed from the summary. Future entries should record the check ID, observed state, applicability, risk, decision, supporting evidence, and review trigger. A scanner mismatch should identify the actual discrepancy between the check logic and effective system configuration.

## Remaining work

Continue hardening, preserve comparable assessment reports, and document actual remediations and exceptions. A final score and completed hardening claim remain pending.

[CyberPi overview](README.md)
