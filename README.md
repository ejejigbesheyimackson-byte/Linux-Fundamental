# Linux-Fundamental
10Alytics Project
# Linux Fundamentals Assignment

## Student Information
**Name:** Mackson Sheyi Ejejigbe  
**Student ID:** CSC26-04-EU-09  
**Course:** Cybersecurity April 2026 Cohort  
**Institution:** 10ALYTICS  
**Submission Date:** 30/04/2026  

---

# Project Overview

This repository contains my Linux Fundamentals Assignment focused on:

- System Information Commands
- Operating System & Hardware Information
- Network Connectivity Testing
- Linux Command Practice
- Documentation using Markdown

---
# Project Description

This project demonstrates practical Linux operating system fundamentals through hands-on command-line exercises and network diagnostics. The lab focuses on collecting system information, analyzing hardware and operating system details, testing network connectivity, and developing familiarity with essential Linux commands.

The objective of this assignment is to build foundational Linux administration and troubleshooting skills commonly used in cybersecurity, system administration, cloud computing, and IT operations.

---

# Project Overview

This project covers core Linux operations including:

- Identifying user and system information
- Exploring operating system and hardware details
- Monitoring memory and disk utilization
- Performing network connectivity tests
- Understanding Linux command-line environments
- Practicing basic Linux administration tasks

The exercises were completed using a Linux environment (Kali Linux) and documented using Markdown for version control and GitHub portfolio presentation.

---

# Tools Used

| Tool | Purpose |
|------|---------|
| Linux Terminal | Executing Linux commands |
| Kali Linux | Operating System Environment |
| Git | Version control |
| GitHub | Repository hosting |
| Markdown | Documentation |
| Ping Utility | Network connectivity testing |
| uname | System information retrieval |
| free | Memory analysis |
| df | Disk usage analysis |
| hostname | Host identification |
| pwd | Current directory display |

---

# Lab Workflow

### Step 1 — System Identification
Collected user and machine information using:

```bash
whoami
hostname
pwd
```

### Step 2 — System & Hardware Inspection
Retrieved operating system and hardware details:

```bash
uname -a
free -h
df -h
```

### Step 3 — Network Connectivity Testing
Verified internet connectivity and measured response time:

```bash
ping -c 2 8.8.8.8
ping -c 4 google.com
```

### Step 4 — Documentation
Captured outputs, screenshots, observations, and documented findings in Markdown for GitHub publishing.

---

# Concepts Covered

This project introduces key Linux and networking concepts:

- Linux File System Navigation
- User & Host Identification
- Linux Kernel Information
- RAM and Storage Monitoring
- Command Line Interface (CLI)
- Network Connectivity Testing
- DNS Resolution
- ICMP Protocol
- Round Trip Time (RTT)
- System Diagnostics
- Technical Documentation

---

# Key Takeaways

By completing this project, I gained practical experience in:

✅ Navigating Linux environments confidently  
✅ Executing and understanding essential Linux commands  
✅ Interpreting system performance metrics  
✅ Testing and validating network connectivity  
✅ Understanding basic networking concepts  
✅ Documenting technical work professionally using GitHub and Markdown  

This project strengthened my foundational Linux and cybersecurity operational skills and serves as part of my practical cybersecurity learning portfolio.

# Assignment Structure

## Part 1 – System Information

### Step 1 – Who Am I and Where Am I?

Commands used:

```bash
whoami
hostname
pwd
```

### Expected Output

| Command | Purpose |
|----------|---------|
| whoami | Displays current username |
| hostname | Shows machine hostname |
| pwd | Shows current directory |

### Results

- Username: `kali`
- Hostname: `kali`
- Current Directory:

```bash
/home/kali/Documents
```

---

## Step 2 – Operating System & Hardware Information

Commands:

```bash
uname -a
free -h
df -h
```

### Findings

- RAM: ~1GB
- Disk Used: 79GB
- Available Disk: 60GB
- Kernel Version:

```bash
Linux Kali 6.16.8
```

---

# Part 2 – Network Connectivity Test

## Step 1 – Ping Google DNS

Command:

```bash
ping -c 2 8.8.8.8
```

### Results

- Average RTT: `66.112 ms`
- Packet Loss: `0%`

---

## Step 2 – Ping Domain Name

Command:

```bash
ping -c 4 google.com
```

### Results

- Resolved IP:

```bash
142.250.140.100
```

### Explanation

The RTT values were similar because both requests travelled through comparable internet routes.

---

# Linux Commands Practiced

```bash
pwd
whoami
hostname
uname
free
df
ping
```

---

# Screenshots

Add screenshots inside:

```text
/images
```

Example:

```md
![whoami output](images/whoami.png)

![ping output](images/ping-test.png)
```

---

# Skills Demonstrated

- Linux Fundamentals
- System Administration
- Network Diagnostics
- Command Line Usage
- Documentation

---

# Repository Structure

```
linux-fundamentals-assignment/
│
├── README.md
├── images/
├── assignment.pdf
└── screenshots/
```

---

# Author

**Mackson Sheyi Ejejigbe**

GitHub: [Add your GitHub profile link]
