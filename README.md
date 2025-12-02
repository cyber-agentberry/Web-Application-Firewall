# Web-Application-Firewall

This repository contains my Web Application Firewall (WAF) lab project, conducted during my internship at Infotact Solutions. The project demonstrates securing a deliberately vulnerable web application (DVWA) using ModSecurity and custom rules.

## Overview
- Set up DVWA on Apache2 with MariaDB backend
- Implemented ModSecurity with OWASP Core Rule Set (CRS)
- Developed custom detection rules for common web vulnerabilities:
- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Configured WAF in DetectionOnly mode for monitoring traffic without blocking
  
## Features
- Detection of SQLi, XSS, and CSRF payloads on DVWA pages
- Audit logs captured in /var/log/apache2/modsec_audit.log
- Clear evidence of attacks being detected with ModSecurity rules

## Repository Contents
- rules/ – Custom ModSecurity rules for SQLi, XSS, and CSRF
- docs/ – Detailed documentation of setup, configuration, attack simulations, and results

## Note
For the full setup process, testing methodology, and analysis, refer to the detailed documentation in the docs/ folder.
