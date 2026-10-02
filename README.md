# Week-4-Web-Application-Penetration-Testing
Networkwalks Cybersecurity Internship
Project Overview

This project documents the activities and findings from Week 4 of my Networkwalks Cybersecurity Internship.

The assessment focused on identifying web application security weaknesses, exposed resources, authentication-related concerns, and document security issues within an authorized testing environment.

The objective was to apply penetration testing methodologies, understand security risks, and recommend appropriate remediation measures.

Objectives
Perform reconnaissance and service enumeration.
Identify exposed web directories and resources.
Examine authentication security.
Identify sensitive information exposure.
Analyze PDF encryption and metadata.
Document vulnerabilities and remediation recommendations.

Tools and Technologies

1.Kali Linux-Testing environment

2.Nmap-Port scanning and service enumeration

3.WhatWeb                              Web technology identification
Gobuster                             Directory discovery
curl                                 HTTP response inspection
John the Ripper                      Password-auditing practice
pdf2john                             PDF hash extraction in the training lab
ExifTool                             Metadata analysis
pdfinfo                              PDF properties
qpdf                                 PDF encryption inspection

Methodology

1. Reconnaissance
Performed initial information gathering to identify the target's accessible services and web technologies.

2. Service Enumeration
Used Nmap to identify exposed ports and service information.

3. Web Application Discovery
Used WhatWeb, Gobuster, and curl to examine application technologies, directories, and HTTP responses.

4. Security Analysis
Reviewed publicly accessible resources, authentication-related behavior, and document security properties.

5. PDF Analysis
Examined PDF encryption settings and metadata using ExifTool, pdfinfo, and qpdf.

6. Reporting
Prepared findings with descriptions, potential impact, provisional severity, and remediation recommendations.

Key Findings

Finding 1 – Publicly Accessible Database Backup
A historical SQL backup was accessible through a public web directory and contained sensitive organizational records.
Risk: Unauthorized disclosure of sensitive information.
Recommendation: Remove backups from the web root and enforce appropriate access restrictions.

Finding 2 – Directory Listing
Directory indexing exposed filenames and application resource structures.
Risk: Information disclosure and increased reconnaissance opportunities.
Recommendation: Disable directory listing and restrict access to sensitive directories.

Finding 3 – Authentication Security Concern
Database-related error behavior and an authentication concern were observed.
Status: Further validation required before confirming a vulnerability classification.
Recommendation: Implement parameterized queries, secure authentication, and appropriate error handling.

Finding 4 – PDF Encryption Analysis
PDF encryption and metadata properties were examined using document analysis utilities.
Recommendation: Apply appropriate encryption, access controls, and secure document storage practices.

Key Learnings
Practical reconnaissance and enumeration.
Understanding web application security misconfigurations.
Identifying sensitive information exposure.
Understanding PDF encryption and metadata.
Evidence-based vulnerability reporting.
Risk assessment and remediation planning.

Disclaimer
This repository is intended for educational and professional portfolio purposes.
All testing was conducted within the authorized assessment scope.
No patient information, credentials, password hashes, database contents, session tokens, or confidential documents are included in this repository.
The findings are summarized for security learning and responsible disclosure.

Author: Prajin P K
Program: Networkwalks Cybersecurity Internship
Focus: Web Application Security | Penetration Testing | Cybersecurity

[Mediroza_Week4_Security_Assessment_Report.pdf](https://github.com/user-attachments/files/32954521/Mediroza_Week4_Security_Assessment_Report.pdf)
