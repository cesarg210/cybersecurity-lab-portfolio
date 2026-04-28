# Cybersecurity Lab Portfolio

## Overview

This repository serves as a central portfolio for my multi-phase cybersecurity lab environment.  
The lab is structured to progressively develop hands-on skills aligned with networking, security operations, detection engineering, vulnerability management, and GRC.

The environment evolves through structured phases:

- 🟢 Network Foundation
- 🟡 Security Hardening & Logging
- 🔵 SIEM Deployment & SOC Operations
- 🔴 Threat Detection & Attack Simulation
- 🟣 Vulnerability Management
- 🟠 Governance, Risk & Compliance

Each phase builds upon the previous one, expanding both technical depth and defensive understanding.

---

## Lab Architecture (High-Level)

                       VMware Virtual Network
                                │
                ┌───────────────┼───────────────┐
                │                               │
         Kali Linux                         Windows Client
        (Attacker VM)                     Domain Workstation
        192.168.85.40                     192.168.85.30
                │                               │
                └───────────────┬───────────────┘
                                │
                        Linux Domain Controller
                        192.168.85.10
                                │
                           SIEM Server
                         192.168.85.20

Virtualized Environment (VMware):

- Windows 11 (Client)
- Linux - Ubuntu Server (Active Directory)
- Kali Linux (Attacker)
- SIEM (Elastic Stack w/ Docker)

Networking:
- NAT & Host-only
- Internal virtual subnet
- Static IP configuration
- Controlled traffic analysis

---

## Phase Roadmap

### 🟢 Phase 1 – Network Foundation
Focus:
- Static IP configuration
- Subnetting practice
- Packet capture (Wireshark / tcpdump)
- DNS traffic analysis
- TCP handshake breakdown
- Kerberos packet flow analysis

Repository:
➡️ [Network+ Homelab](https://github.com/cesarg210/network-plus-homelab.git)

---

### 🟡 Phase 2 – Security Hardening & Logging
Focus:
- Windows advanced audit policies
- Linux firewall configuration
- Authentication failure simulations
- Log analysis and event review

Repository:
➡️ [Security+ Homelab](https://github.com/cesarg210/security-plus-homelab.git)

---

### 🔵 Phase 3 – SIEM Deployment
Focus:
- Elastic Stack installation
- Log ingestion from Windows & Linux
- Alert rule creation
- Incident documentation

Repository:
➡️ [SIEM/SOC Homelab](https://github.com/cesarg210/siem-soc-operations-homelab.git)

---

### 🔴 Phase 4 – Threat Detection & Attack Simulation
Focus:
- Controlled attack simulations (Kali)
- Port scanning & brute force attempts
- IOC identification
- Detection workflow documentation

Repository:
➡️ [Threat Detection Homelab](https://github.com/cesarg210/soc-threat-detection-homelab.git)

---

### 🟣 Phase 5 – Vulnerability Management
Focus:
- OpenVAS deployment
- Vulnerability scanning
- Risk scoring
- Remediation planning

---

### 🟠 Phase 6 – Governance, Risk & Compliance (GRC)
Focus:
- Risk Assessment & Analysis
- Framework Mapping (NIST CSF)
- Security Policy Development
- Compliance & Control Evaluation
- Risk-Based Vulnerability Management
- Executive Reporting
- Deliverables

## Objective

Develop practical, hands-on experience in networking, system security, detection engineering, vulnerability management, and GRC through structured lab progression.

This portfolio documents technical growth over time rather than isolated exercises.

