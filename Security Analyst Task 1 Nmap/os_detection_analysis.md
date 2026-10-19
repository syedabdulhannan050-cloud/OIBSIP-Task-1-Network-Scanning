# Nmap OS Detection Analysis

## Objective
To identify the operating system of my own computer using Nmap.

## Command Used
```bash
nmap -O 127.0.0.1 -oN nmap_os_detection.txt
```

## Results
- Target: 127.0.0.1 (localhost)
- Host status: Up
- Device type: General purpose
- Detected operating system: Microsoft Windows 11
- Estimated OS details: Windows 11 24H2–25H2
- Open TCP ports reported: 4
- Scan duration: Approximately 2.15 seconds

## Security Observations
OS detection provides an estimate of the operating system. Open ports should be reviewed to understand which services are running and whether they are required. The presence of an open port does not automatically indicate a vulnerability.

## Conclusion
Nmap successfully performed OS detection against localhost and identified the system as Microsoft Windows 11. The results are useful for learning network scanning and documenting system exposure.

## Ethical Note
The scan was performed against my own computer for educational purposes.

