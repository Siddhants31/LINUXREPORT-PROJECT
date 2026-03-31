# README.md

# Open Source Audit – Apache HTTP Server

Course: OSS NGMC Capstone Project  
Platform Used: Ubuntu  
Student: Siddhant Shukla  
Registration Number: 24BCE11401  
Slot: B22  
Date of Submission: 31 March 2026  

---

## Project Description

This project presents a detailed audit and analysis of the **Apache HTTP Server**, one of the most widely used open-source web servers in the world. The report explores its history, licensing model, Linux footprint, role in the FOSS ecosystem, and comparison with proprietary alternatives.

The project also includes practical shell scripting tasks performed in **Ubuntu Linux**, demonstrating real-world Linux administration and open-source software auditing.

---

## Objectives

- Study the **origin and philosophy** of Apache HTTP Server
- Understand the **Apache License 2.0**
- Analyze how Apache works in **Linux systems**
- Explore its role in the **LAMP stack**
- Compare open-source and proprietary software
- Develop shell scripts for system analysis and reporting

---

## Software Used

- **Operating System:** Ubuntu
- **Web Server:** Apache HTTP Server
- **Shell:** Bash
- **Package Manager:** APT
- **Tools:** Linux commands and shell scripting utilities

---

## Installation

Install Apache on Ubuntu using:

```bash
sudo apt update
sudo apt install apache2
```

Start the service:

```bash
sudo systemctl start apache2
```

Check service status:

```bash
sudo systemctl status apache2
```

---

## Project Sections

### Part A — Origin and Philosophy

This section explains:

- Why Apache was created
- Problems in earlier web servers
- Open-source ethics
- Freedom vs free software
- Apache licensing model

---

### Part B — Linux Footprint

This section includes:

- Installation method
- Important directories
- Service management
- User/group permissions
- Update model

Important directories:

```text
/etc/apache2/
/var/log/apache2/
/usr/sbin/apache2
```

---

### Part C — FOSS Ecosystem

This section covers:

- Apache dependencies
- Modules like `mod_ssl`
- LAMP stack integration
- Role in modern web infrastructure

---

### Part D — Comparison

Comparison between:

- Apache HTTP Server
- Microsoft IIS

Parameters compared:

- Cost
- Security
- Flexibility
- Source code access
- Community support

---

## Shell Scripts Included

### 1. System Identity Report

Displays:

- Username
- Kernel version
- Uptime
- Date and time
- Linux distribution

---

### 2. FOSS Package Inspector

Checks whether the Apache package is installed using:

```bash
dpkg -l | grep apache2
```

---

### 3. Disk and Permission Auditor

Audits:

- Disk usage
- Directory permissions
- System folders

---

### 4. Log File Analyzer

Reads log files and counts occurrences of keywords like:

```text
error
```

---

### 5. Open Source Manifesto Generator

An interactive script that creates a personalized open-source statement.

---

## Key Learning Outcomes

- Better understanding of **open-source philosophy**
- Practical Linux server administration
- Shell scripting knowledge
- Real-world server deployment basics
- Appreciation for collaborative software development

---

## Conclusion

This project helped in understanding the significance of open-source software and how Apache HTTP Server contributes to modern internet infrastructure. It also improved practical Linux administration and shell scripting skills.

---

## References

- Apache Official Documentation
- GNU Bash Manual
- Open Source Initiative
- GNU Project
- Linux man pages
