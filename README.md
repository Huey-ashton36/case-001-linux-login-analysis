# case-001-linux-login-analysis
Linux SSH Login Investigation – SOC Case Study
# Case 001 - Linux Login Analysis

 Linux SSH Login Investigation

## Overview

This investigation was conducted in a SOC lab environment to analyze SSH authentication activity and determine whether unauthorized access occurred.

## Authentication Checks

### Successful Authentication Check
Command Used
sudo journalctl -u ssh | grep "Accepted"
### Failed authentication Check 
sudo journalctl -u ssh | grep "Failed"

## Investigation Objective

The investigation focused on reviewing Linux authentication logs to identify:

- Failed SSH login attempts
- Targeted usernames
- Source IP addresses
- Whether successful authentication occurred

## Tools Used
- Ubuntu Linux Server
- SSH
- journalctl
- Linux authentication logs
- Terminal

## Investigation Summary
SSH authentication logs were reviewed using:

