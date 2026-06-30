# MSSE 642 – Software Assurance

**Student:** Shawn Wilkinson
**Course:** MSSE 642 – Software Assurance
**Institution:** Regis University
**Professor:** Randall Granier

---

## Overview

This repository contains coursework for MSSE 642, a graduate-level course focused on software assurance, penetration testing, and security analysis. Assignments include hands-on lab work using industry-standard tools such as Kali Linux, Nessus, and Metasploit.

---

## Lab Environment

| Component | Details |
|---|---|
| Host OS | macOS |
| Hypervisor | Oracle VirtualBox (Type 2) |
| Attacker VM | Kali Linux 2026.1 |
| Target VM | Metasploitable |
| Network | VirtualBox NAT Network (`pentestlab`) |
| Scanner | Tenable Nessus |

---

## Repository Structure

```
assignments/
  weekly-projects/
    images/                  # Screenshots for project write-ups
    project-1-labsetup.md    # Assignment #1: Lab Setup
    project-2-threat-analysis.md  # Assignment #2: Threat Analysis
    project-3-penlab-1.md    # Assignment #3: Penetration Testing Part 1
    project-4-penlab-2.md    # Assignment #4: Penetration Testing Part 2
```

---

## Assignments

| Assignment | Description | Status |
|---|---|---|
| [Assignment #1](assignments/weekly-projects/project-1-labsetup.md) | Penetration Testing Lab Setup – Kali Linux + Metasploitable on VirtualBox | Complete |
| [Assignment #2](assignments/weekly-projects/project-2-threat-analysis.md) | Threat Analysis | Complete |
| [Assignment #3](assignments/weekly-projects/project-3-penlab-1.md) | Penetration Testing Part 1 – Nessus & Metasploit | Complete |
| [Assignment #4](assignments/weekly-projects/project-4-penlab-2.md) | Penetration Testing Part 2 – Hiking Club App + OWASP ZAP | Complete |

---

## Project 4 Screenshots

### Hiking Club Web Application

| | |
|---|---|
| ![Home Page](assignments/weekly-projects/images/p4-01-app-home.png) | ![Trails](assignments/weekly-projects/images/p4-02-trails.png) |
| Home Page | Trail Listings |
| ![Login](assignments/weekly-projects/images/p4-03-login.png) | ![Admin Dashboard](assignments/weekly-projects/images/p4-04-admin.png) |
| JWT Login Form | Protected Admin Dashboard |
| ![Events](assignments/weekly-projects/images/p4-05-events.png) | ![Members](assignments/weekly-projects/images/p4-06-members.png) |
| Upcoming Events | Member Directory |
| ![Noticeboard](assignments/weekly-projects/images/p4-07-noticeboard.png) | ![Trail Detail](assignments/weekly-projects/images/p4-08-trail-detail.png) |
| Club Noticeboard | Trail Detail Page |

### Deployment on Kali Linux VM

| | |
|---|---|
| ![Node Install](assignments/weekly-projects/images/p4-06-kali-node-install.png) | ![Docker PostgreSQL](assignments/weekly-projects/images/p4-07-docker-postgres.png) |
| Node.js 22 installed on Kali VM | PostgreSQL running in Docker |
| ![App on Kali](assignments/weekly-projects/images/p4-08-app-on-kali.png) | ![Seed Success](assignments/weekly-projects/images/p4-09-seed-success.png) |
| App running at localhost:5000 on Kali VM | Database seeded successfully |

### OWASP ZAP Penetration Testing

| | |
|---|---|
| ![ZAP Spider](assignments/weekly-projects/images/p4-10-zap-spider.png) | ![ZAP Active Scan](assignments/weekly-projects/images/p4-11-zap-active-scan.png) |
| ZAP Spider – 16 URLs discovered | Active scanner in progress |
| ![ZAP Alerts](assignments/weekly-projects/images/p4-12-zap-alerts.png) | ![CSP Alert Detail](assignments/weekly-projects/images/p4-13-zap-csp-detail.png) |
| Alerts panel – findings by risk level | Missing CSP header alert detail |
| ![ZAP Report](assignments/weekly-projects/images/p4-14-zap-report.png) | |
| ZAP HTML summary report | |

---

## Tools & Technologies

- **Kali Linux** – Penetration testing distribution
- **Oracle VirtualBox** – Type 2 hypervisor for running VMs
- **Tenable Nessus** – Vulnerability scanner
- **Metasploitable** – Intentionally vulnerable target VM
- **Metasploit Framework** – Exploitation framework (built into Kali)
- **Burp Suite** – Web application proxy and information gathering
- **OWASP ZAP** – Web application active scanner
- **Claude Code** – Agentic coding tool used to build the Hiking Club app
