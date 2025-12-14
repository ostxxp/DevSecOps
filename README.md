# Network & Cyber Security — Group Project (F25)

## Project Overview

This repository contains the implementation and proof of concept (PoC) for the **Group Project in Network and Cyber Security (Fall 2025)**.  
The project focuses on applying practical cybersecurity skills in a real-world–like scenario, following the **Security in SDLC / DevSecOps** approach.

The main goal of the project is to demonstrate how automated security testing tools can be integrated into the software development lifecycle to identify, aggregate, and analyze security vulnerabilities in a centralized manner.

---

## Project Goals & Tasks

### Goals
- Build or deploy a **vulnerable application** for security testing
- Integrate **automated security tools** (SAST, SCA, IaC scanning)
- Centralize vulnerability results in a **vulnerability management platform**
- Demonstrate detection, aggregation, and analysis of security issues
- Provide a clear **proof of concept** with reproducible results

### Team Responsibilities
| Role | Responsibility |
|-----|---------------|
| Infrastructure | Environment setup (Docker, services) |
| App Security | Vulnerable application preparation |
| DevSecOps | Integration of security tools |
| Analysis & Report | Results interpretation and documentation |

---

## Methodology & Execution Plan

1. **Environment Preparation**
   - Docker-based infrastructure
   - Vulnerable application deployment
   - Security tools setup

2. **Automated Security Testing**
   - Static Application Security Testing (SAST)
   - Software Composition Analysis (SCA)
   - Infrastructure as Code (IaC) scanning (if applicable)

3. **Vulnerability Management**
   - Uploading scan results via scripts
   - Centralized vulnerability view
   - Alert generation from each integrated tool

4. **Analysis & Validation**
   - Review detected vulnerabilities
   - Validate findings
   - Document results and limitations

---

## Proof of Concept

The PoC demonstrates:
- Successful execution of security scans
- Automated upload of results to the vulnerability management platform
- Visibility of vulnerabilities from multiple tools in one dashboard
- Alerts generated for each integrated security tool

All configurations, scripts, and Docker files are provided in this repository.

---

## Difficulties & Challenges

- Tool compatibility and report format normalization
- Integration issues between scanners and the vulnerability platform
- Environment stability during automated scans
- False positives and result validation

---

## Skills & Knowledge Acquired

- Practical DevSecOps pipeline design
- Hands-on experience with security scanners
- Vulnerability aggregation and management
- Docker-based security testing environments
- Security analysis and reporting

---

## Conclusion

This project demonstrates the importance of integrating security early in the SDLC.  
Automated security testing combined with centralized vulnerability management significantly improves visibility, consistency, and response to security risks.

The implemented solution can be extended further by adding CI/CD integration, additional security tools, and advanced alerting mechanisms.

---

## Demo

A recorded demo of the solution is available **[HERE](https://drive.google.com/file/d/1z6PAj4xPs1kxLVY5_GrhDT36uE2lwlSo/view?usp=sharing)**

---

## Authors

Alena Starikova, Artem Ostapenko, Adelina Karavaeva, Maria Rokkel

Fall Semester 2025

