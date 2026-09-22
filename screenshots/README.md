# Screenshots and evidence

**No lab screenshots are included in this initial publication.** The project currently contains documentation based on the completed-work record. Empty evidence placeholders are not proof of implementation.

## Capture priorities

1. Wazuh view showing the monitored endpoint roles.
2. SSH correlation alert and associated block/unblock evidence.
3. Rule 100003, its corresponding audit event/alert, and T1531 mapping.
4. FIM configuration and representative file-change event.
5. Vulnerability triage example with package applicability and exposure context.
6. CyberPi SCA baseline and subsequent result, with policy context.
7. SSH/UFW hardening and service configuration evidence.
8. Pi-hole DNS filtering and Tailscale connectivity evidence.

Use existing evidence where available. Future test captures should be labeled with their real capture date rather than presented as historical results.

## Publication review

Remove passwords, tokens, API/auth keys, enrollment secrets, SSH private keys, session cookies, identifying public addresses, account/device identifiers, and private DNS/query data. Review usernames, private addresses, and hostnames for disclosure risk. Use permanent redaction and verify the exported image; do not rely on an editable overlay.

Add a caption stating what each artifact demonstrates and its limits. Keep original raw evidence outside this public repository. Configuration artifacts must come from the real lab and be reviewed separately; screenshots do not substitute for deployable configuration.

[Evidence register](../docs/evidence-register.md)
