# Enterprise Cybersecurity Lab Environment (SOC + Offensive Testing)

<p align="center">
  <img src="https://img.shields.io/badge/Lab-Kali%20%7C%20Windows-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-SOC%20%2B%20Offensive%20Security-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Environment-Virtualized-black?style=for-the-badge"/>
</p>

---

## Objective

Establish a controlled virtual lab environment to simulate real-world cybersecurity scenarios, including offensive testing, detection engineering, and SOC monitoring.

---

## Overview

This repository documents the **infrastructure and environment setup** used to simulate enterprise-level cybersecurity scenarios.

The lab serves as the foundation for:

*  Enterprise Authentication Attack Detection (Splunk SIEM)
*  Threat Hunting & Anomaly Detection
*  Detection Engineering workflows

---

## Lab Purpose (Why This Matters)

Unlike basic virtual labs, this environment is designed to replicate a **real enterprise network**, enabling:

* Multi-system attack simulation (Linux, Windows)
* Cross-platform log generation
* Detection and monitoring workflows
* Threat hunting and investigation scenarios

This ensures all projects built on top of this lab reflect **real SOC operations rather than isolated exercises**.

---

## Lab Architecture

```
Attacker (Kali Linux)
        │
        ▼
Internal Virtual Network
        │
 ┌──────────────┐
 │ Windows 10   │
 │ (Target)     │
 └──────────────┘
        │
        ▼
Monitoring & Analysis
(Wireshark / SIEM Integration)
```

---

## Environment Setup

### Systems Deployed

*  Kali Linux (Attacker Machine)
*  Windows 10 (Target / Monitoring System)
*  Internal Virtual Network

---

# Kali Linux Setup

## Deployment

Kali Linux was installed and configured as the primary attacker machine within a virtualized environment.

---

## Kali Linux Environment

<img src="./screenshots/01-kali-desktop.png" width="900">

**Kali Linux VM successfully deployed and configured for offensive security operations**

---

## System Validation

Basic Linux commands were executed to verify system integrity and configuration.

<img src="./screenshots/02-kali-terminal-validation.png" width="900">

**System validation performed using core Linux commands (`uname`, `date`, etc.) confirming proper configuration**

---

## Snapshot Management

A snapshot was created to preserve the system state, enabling rollback during testing scenarios.

<img src="./screenshots/03-kali-snapshot.png" width="900">

**Virtual machine snapshot created to maintain a stable and repeatable testing environment**

---

# Windows 10 Setup

## Deployment

A Windows 10 virtual machine was deployed to simulate a target system and support monitoring and analysis tools.

---

## Security Tool Installation

Wireshark was installed to enable network traffic analysis and packet inspection.

<img src="./screenshots/04-windows-wireshark-install.png" width="900">

**Wireshark installed and configured for network traffic monitoring and analysis**

---

## Snapshot Management

A snapshot was taken to preserve the system configuration before conducting further testing.

<img src="./screenshots/05-windows-snapshot.png" width="900">

**Windows VM snapshot created to ensure system stability and recovery capability**

---

## Security Relevance

This lab environment forms the foundation for all cybersecurity operations performed in subsequent projects, including:

* Reconnaissance
* Network scanning
* Vulnerability assessment
* Exploitation
* SOC detection & monitoring

---

## Related Projects

This lab environment is actively used in:

*  Enterprise Authentication Attack Detection (Splunk)
*  Enterprise Threat Hunting & Anomaly Detection (Splunk)

These projects leverage this infrastructure to simulate real-world attack scenarios and SOC investigations.

---

## Key Takeaway

Building a controlled lab environment is a critical skill for cybersecurity professionals, enabling safe testing, realistic simulations, and hands-on experience with both offensive and defensive security techniques.

---
