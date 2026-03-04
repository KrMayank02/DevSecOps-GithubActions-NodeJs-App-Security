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

<img width="1094" height="688" alt="image" src="https://github.com/user-attachments/assets/0ed69aca-a431-4ef4-b1b8-e58e5e5aa2f1" />

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

<img width="932" height="454" alt="image" src="https://github.com/user-attachments/assets/37436841-f291-48b3-9e5e-ddce96879470" />

--------------------------------------------------------------------------------------------------------------------------------------

<img width="897" height="613" alt="image" src="https://github.com/user-attachments/assets/34c6c4a9-64e0-4466-8554-0ea40b3fe58b" />

-------------------------------------------------------------------------------------------------------------------------------------

<img width="967" height="515" alt="image" src="https://github.com/user-attachments/assets/241653bb-4908-4d21-a14f-37d83c83a092" />

-------------------------------------------------------------------------------------------------------------------------------------

<img width="965" height="512" alt="image" src="https://github.com/user-attachments/assets/7734e0e2-658f-47cc-8fad-c48c5c458381" />

-------------------------------------------------------------------------------------------------------------------------------------

<img width="884" height="404" alt="image" src="https://github.com/user-attachments/assets/73a45a43-58c1-4bf4-a08c-b465514f9655" />

-------------------------------------------------------------------------------------------------------------------------------------

<img width="965" height="373" alt="image" src="https://github.com/user-attachments/assets/0e688d10-0520-469d-ac24-371d62d93dde" />

--------------------------------------------------------------------------------------------------------------------------------------

Artifacts (Reports) uploaded under github repo:

<img width="796" height="584" alt="image" src="https://github.com/user-attachments/assets/2af3ed3a-ef55-43e8-a320-326e8f52332f" />

--------------------------------------------------------------------------------------------------------------------------------------

<img width="898" height="590" alt="image" src="https://github.com/user-attachments/assets/3f912944-82e8-42a0-adaf-d59d327a7964" />

---------------------------------------------------------------------------------------------------------------------------------------

**The Jobs and steps defined under workflow were able to run the Security Scans: SCA, SAST using SNYK tool and perform DAST Scan, Penetration security testing using OWASP ZAP successfully on NodeJS source code.**
**The Artifacts (Scan Reports) were uploaded successfully and displayed vital insights about vulnerabilities/issues in the Node js code/app.**

