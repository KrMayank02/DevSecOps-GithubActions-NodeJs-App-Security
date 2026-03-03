# Securing NodeJS App/Source code with DevSecOps - Principles and Security

**Objective:** To create a GitHub action workflow that will scan and perform SCA, SAST, and penetration security testing on a NodeJS source code.

**Real-time scenario:** CloudInnovate, a startup focused on developing cloud applications for small business customer data management, uses GitHub for version control and prioritizes high security due to the sensitive data involved.
To bolster security, CloudInnovate automates checks via GitHub Actions, including cloning their NodeJS app, confirming build integrity, and performing security scans.
They employ Snyk for Static Application Security Testing (SAST) and Software Composition Analysis (SCA) to find vulnerabilities, and OWASP ZAP for penetration tests. Results are directly logged in GitHub, ensuring swift issue resolution. This strategy not only secures their software but also boosts their reputation, making them more attractive to investors.


### Major Tools, Environment Used in this Project:
- SNYK
- OWASP ZAP
- GitHub Actions
- GitHub


### High Level Tasks/Steps:
-	Fork the Github repository of App source code.
-	Login to Snyk, Enable Snyk Code and Copy Auth Token.
-	Paste the Snyk Token under Github Repository Settings (Secrets).
-	Create Github Actions – Workflow definition file.
-	Run Workflow to perform Security Scans- SAST, SCA and DAST and generate Artifacts (Scan reports).
-	Observe the Workflow Run Status and analyze the Scan reports (Artifacts).

## Output Results Screenshots:

<img width="751" height="498" alt="image" src="https://github.com/user-attachments/assets/63a523ee-3286-4283-ad8c-a8d0a8d216cf" />

------------------------------------------------------------------------------------------------------------------------------------

<img width="752" height="553" alt="image" src="https://github.com/user-attachments/assets/b240dc62-cf34-4080-8ff4-1eb18a5c4f70" />

------------------------------------------------------------------------------------------------------------------------------------

<img width="731" height="662" alt="image" src="https://github.com/user-attachments/assets/3f6f26c2-d0b9-4dab-aa22-37c130a3ece2" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="927" height="408" alt="image" src="https://github.com/user-attachments/assets/0373260a-fbae-421e-ad5e-da051c6be63c" />

--------------------------------------------------------------------------------------------------------------------------------------

Paste the Secret as copied from Snyk Auth Token under github repo:

<img width="870" height="553" alt="image" src="https://github.com/user-attachments/assets/25132022-08c2-4ec7-8981-9a3d2c177676" />

--------------------------------------------------------------------------------------------------------------------------------------

Create Github Actions workflow definition file:

<img width="956" height="443" alt="image" src="https://github.com/user-attachments/assets/ce2e9d4b-f49f-4ea8-a826-f8926ec19777" />

------------------------------------------------------------------------------------------------------------------------------------

perform Security Scans- SAST, SCA and DAST and generate Artifacts (Scan reports):

<img width="957" height="396" alt="image" src="https://github.com/user-attachments/assets/7c9f543f-32e8-423b-9812-1a53947e1319" />

------------------------------------------------------------------------------------------------------------------------------------

Observe the Workflow Run Status and analyze the Scan reports (Artifacts):

<img width="930" height="450" alt="image" src="https://github.com/user-attachments/assets/581ca1be-379b-4690-a9e4-0f2c0ae6b9cb" />

--------------------------------------------------------------------------------------------------------------------------------------

<img width="965" height="457" alt="image" src="https://github.com/user-attachments/assets/be69be42-b8e9-4091-946b-12343d851c55" />

--------------------------------------------------------------------------------------------------------------------------------------











