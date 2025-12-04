# RDP-Bruteforce-Detection-Project
This project demonstrates how a brute-force attack on Windows RDP (Remote Desktop Protocol) is generated, detected, analyzed, and documented using Windows Event Logs.
# RDP Brute-Force Attack Detection – SOC Analyst Project

## 📌 Project Overview
This project demonstrates how to detect, analyze, and investigate an RDP brute-force attack on a Windows 10 machine using Hydra and Windows Security Event Logs.

## 🎯 Objectives
- Simulate attacker brute-force attempts using Hydra
- Capture failed login logs (Event ID 4625)
- Validate successful login (Event ID 4624)
- Review Windows Event Viewer logs
- Create an investigation report
- Demonstrate SOC workflow

## 🧪 Lab Setup
- Windows 10 VM (Target)
- Parrot OS / Kali Linux (Attacker)
- RDP enabled on Windows
- Weak password used for brute-force testing

## 🔥 Attack Simulation
Hydra command used:

hydra -l USERNAME -P /usr/share/wordlists/rockyou.txt rdp://<Windows-IP

logs/ → Windows Security Event Logs screenshots
attack/ → Hydra commands & outputs
configurations/ → Windows security policy settings
report/ → Final SOC investigation report
README.md → Project documentation


## 🕵️ Investigation Summary
- Multiple failed login attempts detected (Event ID: 4625)
- Source IP identified from Windows logs
- Attempted credentials analyzed
- Mapped to MITRE ATT&CK Technique: T1110 (Brute Force)
- Recommendations created to mitigate the attack

## 🛠 Tools Used
- Hydra
- Windows Event Viewer
- Parrot OS
- RDP Protocol
- Microsoft Security Logs

## ✔ Final Output
A complete SOC-level detection and investigation case study.

