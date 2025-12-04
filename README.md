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

