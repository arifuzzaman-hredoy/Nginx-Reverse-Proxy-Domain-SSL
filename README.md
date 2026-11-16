# Nginx Reverse Proxy, Domain & SSL Deployment

A practical, production-oriented DevOps project focused on Nginx administration, reverse proxy configuration, DNS and domain management, HTTPS, SSL/TLS certificates, Let's Encrypt, Certbot, and secure application deployment.

## Project Overview

This project provides hands-on experience with Nginx and production-style web infrastructure.

It covers configuring Nginx as a web server and reverse proxy, connecting domain names to applications, implementing HTTPS, managing SSL/TLS certificates, and troubleshooting deployment issues.

The primary goal is to develop practical infrastructure and deployment skills required for a Junior DevOps Engineer.

## Learning Objectives

- Understand web server architecture and HTTP fundamentals.
- Install and administer Nginx on Ubuntu.
- Configure Nginx server blocks and location directives.
- Host static websites using Nginx.
- Configure Nginx as a reverse proxy.
- Understand upstream servers and load balancing.
- Learn DNS records and domain management.
- Understand HTTPS and SSL/TLS.
- Issue and renew certificates using Let's Encrypt and Certbot.
- Configure HTTP to HTTPS redirection.
- Apply Nginx security best practices.
- Deploy applications behind Nginx.
- Monitor logs and troubleshoot web server issues.
- Implement configuration backup and recovery.

## Technology Stack

| Technology | Purpose |
|---|---|
| Nginx | Web server and reverse proxy |
| Ubuntu Linux | Server operating system |
| Bash | Command-line administration |
| Git | Version control |
| GitHub | Project hosting and documentation |
| DNS | Domain name resolution |
| OpenSSL | SSL/TLS inspection and testing |
| Let's Encrypt | Free SSL/TLS certificates |
| Certbot | Certificate issuance and renewal |
| curl | HTTP request testing |
| dig | DNS troubleshooting |
| Docker | Optional isolated deployment labs |

## Learning Modules

| Module | Topic | Status |
|---|---|---|
| 01 | Web Server Fundamentals | Planned |
| 02 | Nginx Installation and Administration | Planned |
| 03 | Nginx Configuration | Planned |
| 04 | Nginx Reverse Proxy | Planned |
| 05 | Load Balancing | Planned |
| 06 | Domain and DNS Management | Planned |
| 07 | HTTPS and SSL/TLS Fundamentals | Planned |
| 08 | Let's Encrypt and Certbot | Planned |
| 09 | Production Nginx Security | Planned |
| 10 | Application Deployment | Planned |
| 11 | Monitoring and Troubleshooting | Planned |
| 12 | Backup and Recovery | Planned |
| 13 | Final Production Deployment | Planned |

## Repository Structure

```text
Nginx-Reverse-Proxy-Domain-SSL/
├── README.md
├── .gitignore
├── docs/
├── modules/
│   ├── 01-web-server-fundamentals/
│   ├── 02-nginx-installation/
│   ├── 03-nginx-configuration/
│   ├── 04-reverse-proxy/
│   ├── 05-load-balancing/
│   ├── 06-domain-dns/
│   ├── 07-https-ssl-tls/
│   ├── 08-lets-encrypt-certbot/
│   ├── 09-nginx-security/
│   ├── 10-application-deployment/
│   ├── 11-monitoring-troubleshooting/
│   ├── 12-backup-recovery/
│   └── 13-final-deployment/
├── configs/
├── scripts/
└── screenshots/
```

## Practical Labs

Each module will contain practical exercises, configuration examples, command references, troubleshooting scenarios, and screenshots.

## Final Project

Deploy a production-style web application using:

- Ubuntu Server
- Nginx reverse proxy
- Custom domain and DNS configuration
- HTTPS with Let's Encrypt
- Certbot automatic certificate renewal
- HTTP to HTTPS redirection
- Security headers and basic hardening
- Application logging and monitoring

## Security Considerations

- Never commit private keys, passwords, or API tokens.
- Keep SSL/TLS certificates and private keys secure.
- Use least-privilege access.
- Disable unnecessary services and open ports.
- Keep Ubuntu and Nginx updated.
- Validate Nginx configuration before reloading.
- Monitor access and error logs regularly.

## Learning Approach

This repository follows a hands-on learning approach. Every module is designed to build practical knowledge through real-world infrastructure configuration, implementation, testing, and troubleshooting.

## Project Status

**Status:** Learning in Progress

This project is continuously updated as new modules, practical labs, and deployment configurations are completed.

---

**Author:** MD Arifuzzaman Hredoy
**Focus:** DevOps | Linux | Nginx | Networking | Cloud Infrastructure | DevSecOps
