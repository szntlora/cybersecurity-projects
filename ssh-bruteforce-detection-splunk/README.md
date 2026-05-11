# SSH Brute Force Detection and Log Analysis in Splunk

## Overview
This project focuses on analyzing SSH authentication logs using Splunk Enterprise to identify suspicious login activity and potential brute-force behavior.

The analysis was performed in a simulated SOC-style environment using JSON-based SSH logs. SPL queries, visualizations, and alerts were used to investigate failed authentication attempts, successful logins, and suspicious unauthenticated SSH connections.

The full project documentation and analysis is available in PDF format below.

## Objectives

- Analyze SSH authentication logs
- Detect brute-force behavior using SPL queries
- Investigate failed and successful login attempts
- Monitor suspicious SSH activity using dashboards and alerts

## Tools Used
- Splunk Enterprise
- SPL (Search Processing Language)
- Log Analysis
- Dashboard Visualization
- Alert Configuration

## Key Findings
- Multiple failed SSH login attempts were identified from suspicious source IP addresses
- Repeated authentication failures indicated potential brute-force activity
- Successful SSH logins were correlated with previously suspicious IP addresses
- Unauthenticated SSH connections suggested possible scanning or probing activity

## Skills Demonstrated
- SIEM Investigation
- SPL Query Writing
- Authentication Log Analysis
- Threat Detection
- Dashboard and Alert Creation
- SOC-style Investigation

## Documentation

[SSH Log Analysis and Brute Force Detection using Splunk](https://github.com/user-attachments/files/27602729/ssh_log_analysis_splunk_SZL.pdf)
