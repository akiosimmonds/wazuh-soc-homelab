# SSH brute-force correlation

## Completed implementation

A custom Wazuh detection correlates **five invalid SSH authentication attempts within 60 seconds**. Controlled testing generated authentication failures and exercised the detection. Wazuh Active Response `firewall-drop` was implemented to automatically block and subsequently unblock the source.

The exercise connects authentication telemetry, event correlation, and response validation. It is a homelab test of a defined behavior, not a claim of coverage for every password attack.

## Implementation boundaries

The source record does not contain the deployed XML, rule ID, parent rule/decoder, grouping fields, rule level, or frequency counter semantics. It also does not establish how attempts from different sources or users are grouped. The stated threshold records the completed-work summary; exact matching and counter behavior need the actual rule and event sequence for independent reproduction.

## Evidence to add

- Sanitized deployed rule and relevant parent/decoder references.
- Timestamped input events and the corresponding correlation alert.
- Active Response records showing both block and unblock for the test source.
- Rule version and test context sufficient to distinguish expected alerts from duplicates.

No attack commands or synthetic log output are supplied as proof of the completed test.

[Active Response](../../active-response/README.md) · [Detection index](../README.md)
