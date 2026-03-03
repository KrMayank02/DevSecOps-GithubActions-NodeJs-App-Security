# Securing NodeJS App/Source code with DevSecOps - Principles and Security

**Objective:** To create a GitHub action workflow that will scan and perform SCA, SAST, and penetration security testing on a NodeJS source code.

**Real-time scenario:** CloudInnovate, a startup focused on developing cloud applications for small business customer data management, uses GitHub for version control and prioritizes high security due to the sensitive data involved.
To bolster security, CloudInnovate automates checks via GitHub Actions, including cloning their NodeJS app, confirming build integrity, and performing security scans.
They employ Snyk for Static Application Security Testing (SAST) and Software Composition Analysis (SCA) to find vulnerabilities, and OWASP ZAP for penetration tests. Results are directly logged in GitHub, ensuring swift issue resolution. This strategy not only secures their software but also boosts their reputation, making them more attractive to investors.


## Major Tools, Environment Used in this Project:
- SNYK
- OWASP ZAP
- GitHub Actions
- GitHub


## High Level Tasks/Steps:
-	Fork the Github repository of App source code.
-	Login to Snyk, Enable Snyk Code and Copy Auth Token.
-	Paste the Snyk Token under Github Repository Settings (Secrets).
-	Create Github Actions – Workflow definition file.
-	Run Workflow to perform Security Scans- SAST, SCA and DAST and generate Artifacts (Scan reports).
-	Observe the Workflow Run Status and analyze the Scan reports (Artifacts).

