# BlueSheep
Automatic Remote Malware Injection Tool

![https://static.vecteezy.com/system/resources/previews/047/392/479/non_2x/blue-sheep-sits-icon-illustration-vector.jpg](Bluesheep)
## Overview  
BlueSheep is a remote system shutdown tool designed to *permanently disable* a vulnerable system until a new OS is installed. It operates using *Rainbow*, a custom-developed malware that automates the process, allowing a system to be taken down in minutes if vulnerabilities exist.  

---

## Disclaimer  
This tool is strictly for *authorized security research and ethical penetration testing*.  
- Unauthorized use is illegal and may result in legal consequences.  
- The developers hold no responsibility for misuse.  
- This tool must only be used in compliance with applicable laws and regulations.  

---

## Features  
- *Automated Execution* – Scans and exploits vulnerabilities with minimal user input.  
- *Permanent System Shutdown* – Renders the OS inoperable until a full reinstallation.  
- *Custom Malware (Rainbow)* – Developed to execute and persist efficiently.  
- *Cross-Platform Compatibility* – Targets multiple operating systems based on detected weaknesses.  
- *Stealth Mode* – Operates discreetly to reduce detection risks.  

---

## How It Works  
1. *Scan* – Identifies vulnerable systems remotely.  
2. *Deploy* – Injects Rainbow malware into the target system.  
3. *Execute* – Triggers system-level exploits, making the OS unusable.  
4. *Persist* – Ensures that recovery is not possible without reinstalling the OS.  

---

## Installation & Usage  
*Prerequisites:*  
- Ensure you have explicit authorization to test target systems.  
- Install dependencies as listed in the documentation.  

### Installation  
```sh
git clone https://github.com/PhiVault/bluesheep.git
cd bluesheep
chmod +x bluesheep.sh
./bluesheep.sh
