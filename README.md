# AWS Penetration Testing Lab 

This project presents a cloud-based penetration testing laboratory deployed on AWS to simulate realistic cyberattacks, vulnerable enterprise environments, and penetration testing workflows.

## Overview

This project presents a cloud-based penetration testing laboratory deployed on AWS to simulate realistic cyberattacks, vulnerable enterprise environments, and penetration testing workflows.

The lab demonstrates:
- Web application exploitation
- Linux privilege escalation
- Docker misconfigurations
- Internal network pivoting
- Apache Tomcat exploitation
- OWASP Top 10 vulnerabilities
- Penetration testing reporting methodology

The environment was designed and configured manually using AWS infrastructure components including VPCs, subnets, EC2 instances, security groups, routing, and intentionally vulnerable services.

---

## Technologies & Tools

- AWS
- Ubuntu Linux
- Apache Tomcat
- Docker
- PHP
- Apache
- Burp Suite
- Nmap
- Metasploit
- Netcat
- SSH

---

## Vulnerabilities Demonstrated

- CVE-2020-1938 (Apache Tomcat)
- Local File Inclusion (LFI)
- Command Injection
- Insecure Direct Object Reference (IDOR)
- Server-Side Request Forgery (SSRF)
- Server-Side Template Injection (SSTI)
- Cross-Site Scripting (XSS)
- Unrestricted File Upload
- Linux Privilege Escalation
- Docker Privilege Escalation
- SSH Pivoting / Lateral Movement

---

# AWS Architecture

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/image.png" alt="sudo caching">

---

# Internal Network Topology

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/Picture1.png" alt="sudo caching">
---

# Example Screenshots

## Reconnaissance & Enumeration

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/nmap.png" alt="sudo caching">
<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/ffuf.png" alt="sudo caching">
<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/steghide.png" alt="sudo caching">

## Web Exploitation

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/ajpshooter.png" alt="sudo caching">
<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/tomcat.png" alt="sudo caching">
<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/revshell.png" alt="sudo caching">

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/WE1.png" alt="sudo caching">

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/WE2.png" alt="sudo caching">

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/WE3.png" alt="sudo caching">

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/WE4.png" alt="sudo caching">

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/WE5.png" alt="sudo caching">


## Privilege Escalation

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/privesc.png" alt="sudo caching">

## Internal Pivoting

<img src="https://github.com/Barbarossa01/AWS-Penetration-Testing-Lab/blob/main/img/internalPivot.png" alt="sudo caching">

---

# Key Features

- Fully isolated AWS penetration testing environment
- Realistic vulnerable infrastructure
- Manual exploitation workflow
- Proof-of-concept demonstrations
- Vulnerability reproduction steps
- Security recommendations and mitigations
- Professional penetration testing report

---

## Bachelor Thesis

The complete bachelor thesis document is available here:
[Download Full Thesis](./PenetrationTestSimulation-FullThesis.docx)
