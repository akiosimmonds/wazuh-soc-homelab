# CyberPi: Debian 13 security endpoint

CyberPi is a **Raspberry Pi 5 running Debian 13**, deployed as a monitored Wazuh endpoint.

## Completed controls

- SSH public-key authentication.
- Disabled SSH password authentication and root SSH authentication.
- Restricted SSH through UFW and applied additional SSH hardening.
- Remediated unnecessary services.
- Hardened cron permissions and configured login banners.
- Performed Wazuh SCA assessment and ongoing CIS Debian 13 hardening.

Exact SSH directives, permitted source networks, firewall rules, services, and permission values are not included without the actual sanitized configuration. The available record does not establish the placement of Pi-hole or Tailscale on CyberPi.

[CIS progress and risk decisions](cis-hardening.md) · [Network services](../network-services/README.md) · [Back to project](../README.md)
