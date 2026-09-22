# Lessons learned

These takeaways follow from the completed lab activities. They are not substitutes for the pending technical evidence.

## Correlation and response need separate validation

The SSH exercise includes a correlation threshold and a block/unblock lifecycle. Demonstrating a matching alert and demonstrating response behavior are distinct parts of the same case study.

## Tuning is part of detection engineering

Controlled testing and duplicate-alert tuning were part of the custom detection work. A useful case study should preserve the real rule changes and event context rather than inventing a numerical reduction.

## Telemetry quality shapes what can be detected

The privileged account deletion use case relies on Linux audit telemetry reaching Wazuh. Documenting the collection configuration and the matched fields is necessary to explain the rule accurately.

## Scanner output requires system context

CVE triage considered affected components, runtime exposure, and remediation. CIS work included exceptions and architecture-specific mismatches. Both exercises require evidence-based interpretation of findings.

## Hardening is an ongoing process

The CyberPi score moved from 41% to at least 52%, with further work pending. Retaining policy context and actual exception rationale will make the eventual final assessment more useful than a score alone.

[Back to documentation](README.md)
