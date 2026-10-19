# Nmap Scan Analysis

## Objective
To perform a basic service detection scan on my own Windows computer using Nmap.

## Command Used
```bash
nmap -sV 127.0.0.1 -oN nmap_scan_results.txt
```

## Results
- Target: 127.0.0.1 (localhost)
- Host status: Up
- Open TCP ports identified: 4
- Closed TCP ports reported: 996
- Scan duration: Approximately 7.58 seconds

## Services Identified
- Port 135/tcp: Microsoft Windows RPC
- Port 445/tcp: Microsoft-DS (exact identification uncertain)
- Port 902/tcp: VMware Authentication Daemon
- Port 912/tcp: VMware Authentication Daemon

## Security Observations
Open ports indicate services accepting connections. Their presence does not automatically mean the computer is vulnerable. Services should be reviewed to confirm they are required, updated, and protected by suitable firewall rules.

## Conclusion
The Nmap service detection scan completed successfully against localhost. It identified four open TCP ports and provided information about their associated services.

## Ethical Note
The scan was performed against my own computer for educational purposes.

