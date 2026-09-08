# NetSentry Network Security Lab

## 🛡️ Professional Project Overview

NetSentry is a controlled network security assessment project demonstrating network reconnaissance, TCP port discovery, service identification, evidence collection, security analysis, and technical reporting.

The assessment was performed against an authorized Windows virtual machine inside a controlled VMware laboratory environment using Kali Linux and Nmap.

## 🎯 Objectives

- Identify the authorized target system
- Verify network connectivity
- Discover exposed TCP services
- Perform network reconnaissance and port scanning
- Identify discovered services
- Collect assessment evidence
- Analyze potential security exposure
- Document security recommendations
- Produce professional assessment documentation

## 🏗️ Lab Architecture

Kali Linux Security VM
        |
        | Nmap Scan
        v
Windows 10 Target VM

VMware Authorized Lab Environment

## 🎯 Target Information

| Property | Value |
|---|---|
| Environment | Authorized VMware Lab |
| Security VM | Kali Linux |
| Target System | Windows 10 VM |
| Target IP | 192.168.16.129 |
| Assessment Type | Network Security Assessment |

## 🔍 Tools Used

- Kali Linux
- Nmap
- VMware Workstation
- Linux Terminal
- Git
- GitHub

## 🔬 Assessment Methodology

### 1. Scope Definition
Testing was performed only against the authorized Windows virtual machine inside the controlled VMware laboratory.

### 2. Host Identification
The target system was identified and network connectivity was verified.

### 3. Port Scanning
Nmap was used to identify exposed TCP ports and available network services.

### 4. Service Identification
Discovered ports were analyzed to determine associated services.

### 5. Evidence Collection
Relevant scan output and screenshots were preserved within the project evidence structure.

### 6. Security Analysis
Discovered services were reviewed to determine whether their exposure was necessary.

### 7. Reporting
Findings and security recommendations were documented.

## 📊 Findings

### Open TCP Service

| Port | State | Service |
|---|---|---|
| 5357/TCP | Open | WSDAPI |

The discovered service should be reviewed to determine whether it is required. Unnecessary network services should be disabled or appropriately restricted.

## 🛡️ Security Recommendations

- Disable unnecessary network services
- Restrict unnecessary inbound connections
- Configure Windows Firewall appropriately
- Keep the operating system and services updated
- Monitor exposed network services
- Apply network segmentation where appropriate
- Perform regular network security assessments

## 🧠 Skills Demonstrated

- Network Reconnaissance
- Network Enumeration
- TCP Port Scanning
- Nmap
- Service Discovery
- Security Assessment
- Evidence Collection
- Technical Reporting
- Kali Linux
- Linux Command Line
- Git & GitHub
- VMware Laboratory Management

## 📁 Project Structure

NetSentry-Network-Security-Lab/
├── docs/
│   ├── lab-scope.md
│   └── methodology.md
├── evidence/
│   └── README.md
├── reports/
│   ├── scan-summary.md
│   └── security-assessment-report.md
├── scans/
│   ├── README.md
│   ├── initial-scan.txt
│   └── top-100-tcp.txt
├── screenshots/
├── scripts/
├── .gitignore
└── README.md

## ⚠️ Legal Disclaimer

This project was performed exclusively in an authorized and controlled VMware laboratory environment.

Do not perform network scanning, reconnaissance, or security testing against systems or networks without explicit authorization.

## 👤 Author

**Muhammad Rayan**

Cybersecurity Student | SOC Analyst Aspirant | Security Researcher

---

⭐ Built as part of a practical cybersecurity portfolio.
