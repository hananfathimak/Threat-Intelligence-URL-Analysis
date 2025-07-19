# Threat Intelligence Investigation Using Urlscan.io

## Overview
This project demonstrates how **open-source threat intelligence tools** can be used to analyze suspicious URLs, identify phishing or malicious activities, and assess risk levels. The analysis primarily uses **Urlscan.io** with sample URLs collected from **PhishTank**.

## Objective
The goal of this project is to:
- Analyze suspicious domains and URLs for phishing or malicious indicators.
- Use Urlscan.io to gather details like IP addresses, ASN, hosting information, and Google Safe Browsing verdicts.
- Assess risk levels (High, Medium, Low) based on findings.

## Tools Used
- **Urlscan.io** – For URL scanning and threat analysis.
- **PhishTank** – For sourcing real-world phishing URLs.

## Key Findings
- Some URLs were inactive (takedown is common for phishing domains).
- At least one URL was confirmed **malicious** by Google Safe Browsing.
- Several URLs contacted multiple IP addresses and domains, which may indicate suspicious activity.
- **Short-lived TLS certificates (3 months)** were observed, which is common for phishing sites using free SSL certificates.

## Project Structure
- `Threat_Intelligence_Findings.docx` – Contains detailed analysis with screenshots.
- `README.md` – Project summary and instructions.
- `screenshots/` – Folder containing Urlscan.io result screenshots.

## Conclusion
This project highlights the importance of **threat intelligence** in cybersecurity. By leveraging open-source tools like Urlscan.io, we can detect suspicious domains and assess risks based on IP, ASN, and certificate data. These techniques are valuable for SOC analysts and cybersecurity professionals.

## Author
- **Hanan Fathima K**
- Date: July 19, 2025
