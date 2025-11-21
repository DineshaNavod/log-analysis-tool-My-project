# 🌐 ServerLogHub – Synthetic Server Log Collection

**ServerLogHub** is a curated collection of **synthetic server logs** designed for **AI-driven log analytics, cybersecurity research, anomaly detection, and full-stack dashboard projects**.  

These logs simulate **real-world server behavior**, including normal traffic, errors, API calls, and malicious patterns, so you can safely build, test, and demonstrate your security tools or dashboards.

---

## 🔍 Project Overview

ServerLogHub provides datasets that mimic realistic server operations:

- Normal user traffic and browsing patterns  
- System and application errors  
- Authentication and security events  
- API requests with success/failure patterns  
- Malicious behavior: reconnaissance, brute-force, scanning attempts  
- Firewall and system/kernel events  

All logs are **synthetic and safe for public use**, but realistic enough for research, experimentation, or portfolio projects.

---

## 📂 Repository Structure

ServerLogHub/
│
├── README.md
├── LICENSE
│
├── access-logs/
│ ├── access_log_day1.log
│ ├── access_log_day2.log
│ └── README.md
│
├── error-logs/
│ ├── error_log_day1.log
│ └── README.md
│
├── security-auth/
│ ├── auth_log_bruteforce.log
│ ├── auth_log_normal.log
│ └── README.md
│
├── firewall/
│ ├── firewall_events.log
│ └── README.md
│
├── api-gateway/
│ ├── api_requests.json
│ └── README.md
│
└── system/
├── kernel_dmesg.log
└── README.md


---

## 📚 Datasets Included

| Dataset | Description | Format |
|---------|-------------|--------|
| **WebServer Access Logs** | Apache/Nginx-style logs including normal & suspicious activity | `.log` |
| **WebServer Error Logs** | Error messages, warnings, misconfiguration events | `.log` |
| **Auth/Security Logs** | Login attempts, failed logins, brute-force simulations | `.log` |
| **Firewall Logs** | Blocked IPs, port scans, unusual traffic | `.log` |
| **API Gateway Logs** | REST API usage, rate-limit violations, malformed requests | `.json` |
| **System/Kernel Logs** | Kernel-style messages, warnings, and hardware events | `.log` |

---

## 🧩 Key Features

- **Realistic Traffic Patterns:** Normal browsing, API usage, static asset loads  
- **Malicious Activity Simulation:** Recon scanning, brute-force login attempts, SQLi/XSS probes  
- **Variety:** Multiple IP ranges, user-agents, HTTP methods, timestamps, and error types  
- **AI/ML Ready:** Ideal for anomaly detection, AI-driven threat detection, and dashboard testing  

---


