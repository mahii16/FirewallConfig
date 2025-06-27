# Task 4: Configure and Test Windows Firewall

## Objective
Configure basic Windows Firewall rules to allow or block specific traffic and understand their effect.

## Tools Used
- Windows Defender Firewall with Advanced Security
- Command Prompt (`telnet` command for testing)

## Actions Performed
- Viewed and reviewed current firewall rules
- Added a rule to **block port 23 (Telnet)**
- Tested the rule using the `telnet` command
- Removed the rule to restore firewall to default state

## Screenshots
- `current-rules.png`: Existing rules before change
- `block-telnet-rule.png`: Rule added to block port 23
- `telnet-test.png`: Telnet blocked (if tested)
- `delete-rule.png`: Rule removed

## Learnings
- Understood how Windows Firewall filters traffic using ports
- Learned how to manually create, test, and delete custom firewall rules
- Gained hands-on experience with basic network security configurations
