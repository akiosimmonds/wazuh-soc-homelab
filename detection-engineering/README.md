# Detection engineering

Two custom detection use cases are documented from the completed-work record:

| Detection | Confirmed behavior | Validation status |
| --- | --- | --- |
| [SSH brute force](ssh-brute-force/README.md) | Five invalid authentication attempts within 60 seconds | Controlled testing completed; associated response blocks/unblocks the source |
| [Privileged account deletion](privileged-account-deletion/README.md) | Rule 100003 using Linux audit telemetry; T1531 mapping | Developed and validated; controlled testing/tuning addressed duplicate alerts |

Rule XML and raw events are not included in this initial publication. These notes describe implemented behavior without presenting guessed configurations as deployed rules. No quantified false-positive reduction, detection accuracy, or test coverage is claimed.

[Back to project](../README.md)
