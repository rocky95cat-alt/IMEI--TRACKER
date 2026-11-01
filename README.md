# IMEI-TRACKER
A simple and effective tool designed to easily track and recover lost mobile phones using their IMEI number. Use this to ensure the security of your device.


<img width="2000" height="750" alt="IMEI" src="https://github.com/user-attachments/assets/73c423b6-ce75-4722-9824-98780bdcaa90" />

Here is a clear, professional project description for your IMEI lookup and tracking tool designed to run on Kali Linux. You can use this for your GitHub README.md, personal portfolio, or project documentation.

IMEI Tracker & Query Tool for Kali Linux
📌 Overview
This project is a lightweight, command-line and GUI-compatible utility developed for Kali Linux that streamlines the process of querying, validating, and analyzing International Mobile Equipment Identity (IMEI) numbers. Built with security researchers, penetration testers, and forensics analysts in mind, the tool allows users to extract device specifications, check database registries, and run structural validation checks directly from a Linux environment.   
GitHub

🚀 Key Features
TAC (Type Allocation Code) Lookup: Automatically parses the first 8 digits of an IMEI to identify the device manufacturer, brand, model, and hardware specifications.

Luhn Algorithm Validation: Runs mathematical checksum verifications on 14-digit or 15-digit IMEI inputs to confirm formatting authenticity and prevent data entry errors.   
GitHub

Blacklist & Status Checking: Interfaces with data modules to verify if a device has been flagged, reported lost, or blocked on cellular networks.   
GitHub

Kali Linux Integration: Fully optimized for Debian-based penetration testing distributions, running smoothly via Python 3 and standard Linux terminal packages.   
GitHub

Modular Scripting: Can be integrated into larger OSINT (Open Source Intelligence) or digital forensics pipelines.

💻 System Requirements & Dependencies
Because this tool is built for Kali Linux, it requires Python 3 and a few standard libraries to handle web requests and data parsing.

Tested Environment
OS: Kali Linux (Rolling / 2026 release)

Language: Python 3.x

Required Libraries
requests (for API querying and web lookups)   
GitHub

beautifulsoup4 (for HTML parsing where applicable)   
GitHub

PyQt5 (Optional) (if utilizing the graphical user interface version)

🛠️ Installation & Setup on Kali Linux
Open your terminal in Kali Linux and follow these steps to clone and set up the tool:

Bash
# 1. Update system packages and install Git / Python3
sudo apt update && sudo apt install git python3 python3-pip -y

# 2. Clone your repository IMEI--TRACKER
git clone https://github.com/Rockyrook96/IMEI--TRACKER.git

cd IMEI--TRACKER

# 3. Install required Python dependencies
pip3 install -r requirements.txt

# 4. Run the tool
python3 imei.py
⚠️ Disclaimer
This tool is created strictly for educational purposes, defensive security research, and authorized digital forensics. Unauthorized tracking of mobile devices or exploiting telecommunication networks without explicit consent is illegal. The developer assumes no liability for misuse.
