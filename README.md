<img width="1914" height="944" alt="image" src="https://github.com/user-attachments/assets/78e46e1a-fa85-4bf9-9a3d-e5453c1742e6" />


click Here For The Prototype : https://socsecurity.netlify.app/ 
Username : authuser
password: 1234

# 🚀 SOC Platform Enhancement  
# Automated Telemetry Ingestion Pipeline

## 🛡️ Security Operations Center (SOC) Platform

A complete upgrade of the SOC telemetry ingestion architecture, transforming the platform from a manual prototype workflow into an automated, background-driven security monitoring system.

The new pipeline introduces:

- Automated log ingestion
- Background forensic processing
- Signature-based threat detection
- MongoDB telemetry storage
- Interactive analyst dashboard
- Single-command deployment workflow

---

# 📌 Project Overview

## Previous Architecture Problem

The earlier SOC prototype required multiple independent processes running simultaneously:


This created operational overhead:

- Manual script execution
- Multiple terminal dependency
- Manual log movement
- No continuous monitoring
- Difficult deployment process

---

# 🚀 New Automated Architecture

The platform has been redesigned into a self-contained ingestion ecosystem.

## New Execution Model

Only one command is required:

```powershell
python manage.py runserver 8080

Django Application
        |
        |
        +----------------+
        |                |
        ▼                ▼

Web Dashboard     Background SOC Worker

                         |
                         ▼

                  Log Monitoring Engine

                         |
                         ▼

                   Threat Analyzer

                         |
                         ▼

                    MongoDB Storage
