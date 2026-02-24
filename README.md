# Cybersecurity Lab Portfolio

## Overview

This repository serves as a central portfolio for my multi-phase cybersecurity lab environment.  
The lab is structured to progressively develop hands-on skills aligned with networking, security operations, detection engineering, and vulnerability management.

The environment evolves through structured phases:

- 🟢 Network Foundation (Network+ aligned)
- 🟡 Security Hardening & Logging (Security+ aligned)
- 🔵 SIEM Deployment & SOC Operations
- 🔴 Threat Detection & Attack Simulation (CySA+ aligned)
- 🟣 Vulnerability Management

Each phase builds upon the previous one, expanding both technical depth and defensive understanding.

---

## Lab Architecture (High-Level)

Virtualized Environment (VMware):

- Windows 11 (Client / Target)
- Ubuntu Server (Infrastructure / Log Server / AD)
- Kali Linux (Attacker – later phase)
- SIEM (Wazuh – later phase)

Networking:
- NAT networking
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
➡️ `network-plus-homelab`

---

### 🟡 Phase 2 – Security Hardening & Logging
Focus:
- Windows advanced audit policies
- Linux firewall configuration
- Authentication failure simulations
- Log analysis and event review

---

### 🔵 Phase 3 – SIEM Deployment
Focus:
- Wazuh installation
- Log ingestion from Windows & Linux
- Alert rule creation
- Incident documentation

---

### 🔴 Phase 4 – Threat Detection & Attack Simulation
Focus:
- Controlled attack simulations (Kali)
- Port scanning & brute force attempts
- IOC identification
- Detection workflow documentation

---

### 🟣 Phase 5 – Vulnerability Management
Focus:
- OpenVAS deployment
- Vulnerability scanning
- Risk scoring
- Remediation planning

---

## Objective

Develop practical, hands-on experience in networking, system security, detection engineering, and vulnerability management through structured lab progression.

This portfolio documents technical growth over time rather than isolated exercises.
