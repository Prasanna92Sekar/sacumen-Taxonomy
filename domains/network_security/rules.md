# Network Security Labeling Rules

- IF action == "BLOCK" → event_type = firewall_deny
- IF dst_port == 22 AND action == "BLOCK" → attack_type = ssh_bruteforce
- IF repeated denies from same IP → risk_level = high
