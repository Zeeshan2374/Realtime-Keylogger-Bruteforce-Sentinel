# 🚨 Realtime Keylogger & Bruteforce Sentinel

> A real-time threat detection and monitoring framework built using Sysmon, Winlogbeat, Elasticsearch, and Kibana to detect keylogger activity and brute-force attacks through custom SIEM correlation rules, automated email alerts, and security dashboards.

---

# Overview

Realtime Keylogger & Bruteforce Sentinel is a Security Operations Center (SOC) monitoring project designed to identify malicious activity on Windows endpoints and generate actionable alerts in real time.

The project leverages Sysmon for endpoint telemetry, Winlogbeat for log forwarding, Elasticsearch for centralized log storage, and Kibana Security for visualization, detection engineering, and incident investigation.

The framework focuses on detecting:

* Keylogger Activity
* Brute Force Attacks
* Suspicious Process Creation
* Authentication Abuse
* Endpoint Threats

---

# Features

### Endpoint Monitoring

* Sysmon Event Collection
* Process Monitoring
* Command-Line Monitoring
* Security Event Collection

### Threat Detection

* Keylogger Detection Rules
* Brute Force Detection Rules
* Event Correlation
* Risk Scoring

### Alerting

* Real-Time Alerts
* Email Notifications
* High Severity Events
* Incident Visibility

### Investigation

* Kibana Security Dashboards
* Alert Timeline Analysis
* Event Correlation
* Threat Hunting Support

---

# Technology Stack

## Endpoint Monitoring

* Sysmon

## Log Collection

* Winlogbeat

## SIEM

* Elasticsearch
* Kibana Security

## Alerting

* Email Notifications
* Detection Rules

## Operating Systems

* Windows 10
* Kali Linux

---

# Detection Capabilities

## Keylogger Detection

Detects:

* Suspicious keyboard monitoring tools
* Known keylogger processes
* Malicious executable execution
* Unauthorized monitoring activity

## Brute Force Detection

Detects:

* Multiple Failed Logins
* Repeated Authentication Failures
* Account Targeting Attempts
* Login Abuse Patterns

---

# Architecture

Windows Endpoint
│
▼
Sysmon
│
▼
Winlogbeat
│
▼
Elasticsearch
│
▼
Kibana Security
│
├── Detection Rules
├── Alerts
├── Dashboards
└── Email Notifications

---

# Security Monitoring Workflow

1. Endpoint activity is recorded by Sysmon.

2. Winlogbeat forwards logs to Elasticsearch.

3. Kibana Security continuously analyzes incoming events.

4. Custom detection rules identify suspicious activity.

5. High-risk events generate alerts.

6. Email notifications are sent to security analysts.

7. Analysts investigate alerts using Kibana dashboards.

---

# Skills Demonstrated

* SOC Operations
* SIEM Engineering
* Detection Engineering
* Threat Hunting
* Incident Response
* Windows Security Monitoring
* Endpoint Visibility
* Elastic Stack Administration
* Security Analytics
* Alert Management

---

# MITRE ATT&CK Mapping

### Brute Force

Technique:
T1110 – Brute Force

### Keylogger Activity

Technique:
T1056 – Input Capture

### Process Monitoring

Technique:
T1059 – Command and Scripting Interpreter

### Endpoint Monitoring

Technique:
T1082 – System Information Discovery

---

# Learning Outcomes

This project demonstrates practical experience in:

* Building a SIEM pipeline
* Endpoint telemetry collection
* Detection rule development
* Threat monitoring
* Alert engineering
* Incident investigation
* Security analytics

---

# Author

Zeeshan Alam

Cybersecurity Analyst | SOC Analyst | Threat Hunter

LinkedIn:
[www.linkedin.com/in/zeeshanalam21](http://www.linkedin.com/in/zeeshanalam21)

Email:
[zalam5577@gmail.com](mailto:zalam5577@gmail.com)
