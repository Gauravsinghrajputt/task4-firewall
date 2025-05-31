# task4-firewall
 Configuring and testing basic firewall rules using Windows Defender Firewall to block insecure ports like Telnet (port 23). Includes screenshots and explanation of each step.


# Task 4 - Firewall Rule Configuration (Windows)

## Objective:
To configure and test a basic firewall rule to block network traffic on a specific port.

## Platform Used:
Windows 10 – Windows Defender Firewall with Advanced Security

## Tools:
- Windows Defender Firewall (GUI)

## Task Steps:

1. Opened **Windows Defender Firewall with Advanced Security**.
2. Created a **New Inbound Rule**:
   - Rule Type: Port
   - Protocol: TCP
   - Port: 23 (Telnet)
   - Action: Block the connection
   - Applied to: Domain, Private, and Public profiles
   - Rule Name: **Block Telnet (Port 23)**
3. Took screenshots at each step as proof of configuration.
4. Verified that the rule was successfully created and applied.
5. Removed the rule afterward to restore the firewall to its original state.

## Purpose:
This task demonstrates how to manually control network traffic using firewall rules. Port 23 (Telnet) is blocked because it’s an outdated and insecure protocol that should not be used on modern networks.

## Outcome:
Gained hands-on experience in firewall configuration and an understanding of how to filter traffic based on ports.

## Screenshots:
All related screenshots of the rule creation process are included in this repository.
