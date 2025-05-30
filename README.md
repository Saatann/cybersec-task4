# cybersec-task4
Setup and Use a Firewall on Windows.
# Windows Firewall Rule Configuration

## Objective
Demonstrate basic firewall rule creation using Windows Defender Firewall.

## Tasks Performed
- Blocked inbound traffic on TCP port 23 (Telnet).
- Tested the rule using Telnet client (connection failed as expected).
- Created a rule to allow SSH on port 22.
- Removed test rule to restore default firewall state.

## Tools Used
- Windows Defender Firewall
- Telnet Client

## Screenshots
- `firewall_rule_block_telnet.png` – rule created
- `telnet_test_failed.png` – telnet test showing blocked connection
- `firewall_rule_allow_ssh.png` – SSH allow rule

## Summary
Windows Firewall filters traffic based on user-defined rules for ports, programs, or services. By setting up port-specific blocks or allows, we can control network access to services running on a system.
