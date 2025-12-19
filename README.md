1. Running ZAP (OWASP ZAP - Zed Attack Proxy)

OWASP ZAP is a tool for finding security vulnerabilities in web applications. Here's how to run it:

Install ZAP:
Follow the installation guide here: ZAP Install Guide
.

Start ZAP:
Open the ZAP application and configure it to test the app running on http://localhost:3000.

Run ZAP Scan:
In ZAP, you can configure a spider scan or active scan to find vulnerabilities in the app.

2. Running Semgrep with Base Rules

Semgrep
 is a fast, open-source static analysis tool to find vulnerabilities in your codebase.

Install Semgrep:
Follow the guide to install Semgrep:

pip install semgrep


Run Semgrep with Base Rules:
Navigate to the project folder and run Semgrep using the following command to apply its base security rules:

semgrep scan --  config auto .


This will scan the entire application for known vulnerabilities, including issues like SQL Injection, Cross-Site Sc 
this is some commands we fin vulnerabilites with 
curl "http://localhost:5000/v1/redirect"
curl "http://localhost:5000/v1/user/1"
