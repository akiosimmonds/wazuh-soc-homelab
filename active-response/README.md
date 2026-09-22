# Wazuh Active Response

## Completed behavior

Wazuh Active Response was implemented with `firewall-drop` in conjunction with the custom SSH brute-force detection. Controlled testing validated automatic blocking and subsequent unblocking of the source.

The completed exercise covers the response lifecycle: detection, block, and removal of the block. It does not establish response latency, effectiveness against distributed attacks, or production reliability.

## Configuration not yet published

The available record does not include the response duration, execution host, firewall backend, allowlist, command definition, or trigger configuration. A guessed response stanza could misrepresent the lab and is therefore not provided.

## Evidence to add

Publish sanitized trigger configuration and timestamped response records showing the matching alert, block operation, and later unblock. Include the actual execution location and configured duration. Preserve only the details needed to explain the test and remove credentials and identifying network details.

[SSH detection](../detection-engineering/ssh-brute-force/README.md) · [Back to project](../README.md)
