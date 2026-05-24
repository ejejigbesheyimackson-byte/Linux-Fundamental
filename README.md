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
