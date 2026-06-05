# 🔐 Vulnerability Assessment Report

**Author:** Mokshagna  
**Program:** Future Interns — Cybersecurity Internship Task 1  
**Date:** May 2026  
**Target:** zero.webappsecurity.com  

## 📋 About This Assessment
This repository contains the findings of a passive, read-only ethical vulnerability assessment performed on a legally permitted test website. The goal of this assessment was to identify security misconfigurations, exposed vulnerabilities, and HTTP/SSL weaknesses without performing any active exploitation.

## 🛠️ Tools Used
* Nmap & Zenmap GUI (Port and service discovery)
* OWASP ZAP (Passive vulnerability scanning)
* SecurityHeaders.com (HTTP header analysis)
* SSL Labs (SSL/TLS configuration check)
* Mozilla Observatory (Web security scoring)
* Browser DevTools (Manual header inspection)

## 📊 Findings Summary
* **Total Vulnerabilities:** 10
* **High Risk:** 3 (e.g., Expired SSL, Missing Content-Security-Policy)
* **Medium Risk:** 5 (e.g., Missing X-Frame-Options, Exposed Server Version)
* **Low Risk:** 2

## 📁 Repository Contents
* `report.pdf` — The complete 14-page Vulnerability Assessment Report.
* `evidence/` — Screenshots of tool outputs, scan results, and header inspections.

## ⚠️ Ethics Statement
This assessment was conducted strictly on a legally permitted, intentionally vulnerable test target. No exploitation, brute-forcing, or data extraction was performed.
