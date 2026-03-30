# Azure Cloud Security Lab

## Overview
This project demonstrates how to secure a Linux virtual machine deployed in Microsoft Azure.

The lab simulates real-world cloud security practices including SSH hardening, firewall configuration, brute force protection, and file integrity monitoring.

## Technologies Used
- Microsoft Azure
- Ubuntu Linux
- SSH
- UFW Firewall
- Fail2Ban
- AIDE (Advanced Intrusion Detection Environment)

## Security Implementations

### SSH Hardening
Modified SSH configuration to improve system security.

### Firewall Configuration
Configured UFW firewall to allow only necessary services.

### Fail2Ban
Installed Fail2Ban to automatically block IP addresses attempting brute force attacks.

### AIDE File Integrity Monitoring
Implemented AIDE to detect unauthorized changes to system files.

### Log Analysis
Used system logs to identify brute force attacks:
