# Windows Host Exposure Analysis using Nmap

## Overview
This project focuses on analyzing exposed services and open ports on a Windows host using Nmap.

The goal was to identify potential security risks, investigate exposed network services, and understand how different scan types reveal additional attack surface information.

The full project documentation and analysis is available in PDF format below.

## Objectives
- Perform advanced and full TCP port scans
- Identify exposed services on a Windows host
- Analyze SMB and RPC-related security risks
- Compare default and full scan results

## Tools Used
- Nmap
- TCP Port Scanning
- Service Enumeration
- Windows Networking Analysis

## Key Findings
- Port 135 (MSRPC) and Port 445 (SMB) were exposed
- SMB may present risks related to lateral movement and known vulnerabilities
- Full port scans identified additional high-numbered dynamic ports
- Default scans may not reveal the complete attack surface

## Skills Demonstrated
- Network Reconnaissance
- Port Scanning
- Service Enumeration
- Attack Surface Analysis
- Security Risk Assessment

## Documentation
[Nmap Network Scan Analysis - Windows Host](https://github.com/user-attachments/files/27602502/nmap_windows_host_analysis_SZL.pdf)
