# 🔐 ParoCyber Ethical Hacking – Capstone Project
**Internal Security Assessment of Metasploitable2**

## Overview
A professional penetration test conducted over one week against a 
Metasploitable2 VM from Kali Linux, covering 5 assessment phases.

## Phases Covered
| Phase | Focus | Key Tools |
|-------|-------|-----------|
| 1 | Information Gathering & Enumeration | Nmap, Gobuster, Enum4linux |
| 2 | Password Security Assessment | John the Ripper, Hydra |
| 3 | Vulnerability Assessment | Metasploit, Manual Analysis |
| 4 | Social Engineering Simulation | SET (Social-Engineer Toolkit) |
| 5 | Risk Analysis & Recommendations | Risk Matrix, Top 10 Remediations |

## Overall Risk Rating: 🔴 CRITICAL

## Key Findings
- 17+ vulnerabilities identified including 6 Critical CVEs
- 7/7 accounts had weak/default passwords — all cracked in <60 seconds
- 3 paths to unauthenticated root shell
- ~90% phishing simulation success rate

## Report
📄 Full report available in `/report/`

## Disclaimer
This assessment was conducted in an isolated lab environment 
for educational purposes only as part of the ParoCyber 
Ethical Hacking course.
