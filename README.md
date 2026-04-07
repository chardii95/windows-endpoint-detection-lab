# 🛡 Windows Endpoint Detection Lab

## 📌 Overview
This project simulates a real-world account compromise scenario and demonstrates how a SOC analyst investigates suspicious activity using Windows Event Logs.

## 🎯 Objectives
- Detect brute-force login attempts
- Identify unauthorized account creation
- Detect privilege escalation
- Build an investigation timeline
- Perform SOC-style analysis

## 🧪 Scenario
A simulated attack was conducted where:
- Multiple failed login attempts were generated
- A new user account was created
- The user was added to the Administrators group
- Suspicious activity was executed

## 🔍 Tools Used
- Windows Event Viewer
- Command Prompt
- PowerShell

## 📊 Key Findings
- Event ID 4625: Multiple failed login attempts detected
- Event ID 4720: New user account created
- Event ID 4728/4732: User added to Administrators group

## 🚨 Conclusion
The activity indicates a potential account compromise with privilege escalation, which would be classified as a high severity incident in a real SOC environment.
