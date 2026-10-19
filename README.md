# Oasis Infobyte Internship — Task 1
## Basic Network Scanning with Nmap

### 1. Project Overview
This project uses Nmap to scan my own computer and identify open ports, associated services, and operating-system information.

### 2. Objectives
- Perform a basic network scan.
- Identify open ports and services.
- Perform service-version detection.
- Attempt operating-system detection.
- Save scan results and document security observations.

### 3. Tools Used
- Nmap
- Windows PowerShell
- Windows computer

### 4. Commands Used

```powershell
nmap 127.0.0.1
nmap -sV 127.0.0.1
nmap -O 127.0.0.1
```

The target `127.0.0.1` is the loopback address, which refers to my own computer.

### 5. Files and Evidence
- `nmap_scan_results.txt` — saved scan results.
- `nmap_os_detection.txt` — saved OS detection results.
- `scan_analysis.md` — analysis of the scan findings.
- `os_detection_analysis.md` — analysis of OS detection.
- `Screenshots/` — screenshots showing scan evidence.

### 6. Security Observations
Open ports indicate that services may be listening for connections. Their presence is not automatically a vulnerability. Each service should be checked to confirm that it is necessary, appropriately configured, and protected.

See `scan_analysis.md` for port-specific findings and potential risks.

### 7. Ethical Use
I performed these scans against my own computer. Nmap should only be used on systems and networks that I own or have explicit permission to assess. Scanning without authorization may violate policies or laws.

### 8. Conclusion
This project helped me understand basic port scanning, service detection, OS detection, saving scan output, and documenting security observations. Nmap supports network inventory and security assessments by helping identify exposed services.

### 9. Reference
Official Nmap documentation: https://nmap.org/book/

### Internship
Oasis Infobyte — Security Analyst / Cyber Security Internship# OIBSIP
CyberSecurity Internship Repo
