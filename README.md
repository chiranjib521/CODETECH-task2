NAME-CHIRANJIB NAYAK
COMPANY-CODETECH IT SOLUTIONS
ID-CT04DZ554
DURATION-18TH JULY-18TH AUGUST2025
MENTOR-NEELA SANTHOSH



Project Overview: Web Application Vulnerability Scanner
Objective
The Web Application Vulnerability Scanner is a Python-based tool designed to identify common security vulnerabilities in web applications, such as:

SQL Injection (SQLi)

Cross-Site Scripting (XSS)

The primary goal of this project is to enhance web security by proactively scanning websites for vulnerabilities before attackers can exploit them.

Key Features
Website Crawling:

Automatically visits and collects all reachable links from the target website.

Form Detection:

Extracts and analyzes HTML forms to identify potential input points for attackers.

SQL Injection Testing:

Submits malicious SQL payloads in form fields to detect if the application is vulnerable to database exploitation.

XSS Testing:

Injects JavaScript payloads to check if the site reflects them, indicating an XSS vulnerability.

Automated Scanning:

Recursively scans the entire website with minimal user input.

Technology Stack
Programming Language: Python

Libraries Used:

requests → for sending HTTP requests

BeautifulSoup (bs4) → for parsing and extracting forms/links from HTML

urllib.parse → for managing URLs during website crawling

Working Process
Input Target URL
The user provides a website URL to scan.

Website Crawling
The tool collects all links on the website.

Form Analysis
Each page is scanned for input forms that could be vulnerable.

Vulnerability Testing

Injects SQL payloads to detect SQLi.

Injects JavaScript payloads to detect XSS.

Report Generation
The tool prints a summary of discovered vulnerabilities in the console.

Deliverable
A Python-based automated vulnerability scanner that helps web developers and security analysts detect and fix vulnerabilities early, reducing the risk of exploitation.




