# Task 1 – Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a basic network scan using Nmap, identify open ports and running services on a local machine, and understand the security risks associated with exposed services.

## Tools Used
- Nmap
- Windows PowerShell (or Command Prompt)
- Windows Operating System

## What is Nmap?
Nmap (Network Mapper) is an open-source network scanning tool used to discover hosts, identify open ports, detect running services, and gather information about network devices.

## Why Network Scanning Matters
Network scanning helps identify active devices, open ports, and running services. It allows administrators to detect security risks, monitor network health, and improve system security.

## Installation Steps
1. Download Nmap from the official website.
2. Install Nmap using the default installation settings.
3. Verify the installation by running:
   ```
   nmap --version
   ```

## Commands Used
### Basic Scan
```
nmap 127.0.0.1
```

### Service Version Scan
```
nmap -sV 127.0.0.1
```

### OS Detection Scan
```
nmap -O 127.0.0.1
```

## Files Included
- README.md
- nmap_scan_results.txt
- screenshots/

## Ethical Use
Nmap should only be used on systems that you own or have permission to scan. Unauthorized scanning of external systems is unethical and may violate laws or organizational policies.

## Conclusion
This task helped me understand how to perform basic network scanning using Nmap, identify open ports and services, and analyze potential security risks.
