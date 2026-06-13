# ParoCyber-Ethical-Hacking-Capstone-

## Overview
Internal security assessment conducted on a Metasploitable2 target (Web App Test-badr) 
via TryHackMe's Basic Pentesting room as part of the ParoCyber Ethical Hacking programme.

## Tools Used
- Nmap (port scanning & vulnerability scripts)
- SSH (credential testing)
- Social-Engineer Toolkit (SET) v8.1.3
- TryHackMe AttackBox (Kali Linux environment)

## Phases Covered
1. **Information Gathering** – Nmap service enumeration
2. **Password Security** – SSH brute force & /etc/shadow analysis
3. **Vulnerability Assessment** – Nmap NSE vuln scripts, CVE identification
4. **Social Engineering** – Credential harvesting simulation using SET

## Key Findings
- 6 open ports including SSH, HTTP, Samba, Apache Tomcat
- Default credentials on kay account (CRITICAL)
- Slowloris DoS vulnerability – CVE-2007-6750 (CRITICAL)
- Exposed /development/ directory and Tomcat manager

## Report
Full assessment report available in `/report/ParoCyber_Security_Assessment_Report.pdf
