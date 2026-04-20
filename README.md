# Enterprise IT Infrastructure Lab (SOC + Offensive Testing)

<p align="center">
  <img src="https://img.shields.io/badge/Lab-Kali%20%7C%20Windows-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-IT%20Operations%20%2B%20Security-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Environment-Virtualized-black?style=for-the-badge"/>
</p>

---

## Objective

Build a controlled enterprise lab environment to simulate **real-world IT operations, system troubleshooting, network issues, and security scenarios**.

---

## Overview

This lab represents a **multi-system enterprise environment** used for:

- System deployment and configuration  
- Network troubleshooting and diagnostics  
- Endpoint monitoring and issue resolution  
- Security testing and SOC-based detection workflows  

---

## Why This Lab Matters

Unlike basic labs, this environment simulates **real enterprise infrastructure**, allowing:

- Troubleshooting across multiple systems (Linux + Windows)  
- Network issue diagnosis and resolution  
- Authentication and system-level debugging  
- Log-based analysis and monitoring  

 This reflects **real IT support + field service work**, not just theoretical labs.

---

##  Lab Architecture

```
Attacker (Kali Linux)
        │
        ▼
Internal Virtual Network
        │
 ┌──────────────┐
 │ Windows 10   │
 │ (Endpoint)   │
 └──────────────┘
        │
        ▼
Monitoring & Analysis
(Wireshark / Logs / SIEM)
```

---

##  Environment Setup

### Systems Deployed

- Kali Linux (Testing / Diagnostics System)  
- Windows 10 (Endpoint System)  
- Internal Virtual Network  

---

#  Kali Linux Setup

## Deployment

Kali Linux configured as a **testing and diagnostic system** within the environment.

---

## System Validation

<img src="./screenshots/01-kali-desktop.png" width="900">

Basic system validation performed to confirm OS functionality and configuration.

---

<img src="./screenshots/02-kali-terminal-validation.png" width="900">

Commands such as `uname`, `date`, and system checks were used to verify environment readiness.

---

## Snapshot Management

<img src="./screenshots/03-kali-snapshot.png" width="900">

Snapshot created to ensure **system recovery and repeatable testing scenarios**.

---

#  Windows 10 Setup

## Deployment

Windows 10 VM deployed as an **enterprise endpoint system** for testing and troubleshooting.

---

## Tool Installation

<img src="./screenshots/04-windows-wireshark-install.png" width="900">

Wireshark installed for **network traffic monitoring and diagnostics**.

---

## Snapshot Management

<img src="./screenshots/05-windows-snapshot.png" width="900">

Snapshot created to maintain a stable baseline configuration.

---

##  IT Operations Use Cases

This lab enables hands-on experience with:

- Diagnosing network connectivity issues (DNS, IP, routing)  
- Troubleshooting system performance and stability issues  
- Investigating authentication failures across systems  
- Endpoint monitoring and issue resolution  
- Log-based root cause analysis  

---

##  Security & SOC Integration

This environment also supports:

- Attack simulation (brute force, scanning, exploitation)  
- Threat detection and log analysis  
- SIEM integration (Splunk)  
- Incident investigation workflows  

---

##  Related Projects

- Enterprise Authentication Attack Detection (Splunk SIEM)  
- Threat Hunting & Detection Engineering Labs  

---

##  Key Takeaway

This lab demonstrates the ability to:

✔ Deploy and manage systems  
✔ Troubleshoot real-world IT issues  
✔ Analyze system and network behavior  
✔ Integrate security monitoring into operations  

---
