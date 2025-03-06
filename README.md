# BlueSheep
Automatic Remote Malware Injection Tool

![Screenshot 2025-03-07 000217.png](<https://media-hosting.imagekit.io//075d1cb9ad3e49e3/Screenshot 2025-03-07 000217.png?Expires=1835894223&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=URfyN17kqemFQJYByUOvXEFo9kBpRQgGoolKUOs1PMKBxPpVb7mXZSgXyTfVVcgHtoGVx7-h3EV~nCVTYl1VejkI9YHjQEfnthiWHF5HrTr0E7~okr48qUgoVonkQraOJTCioDOC6A5utOaELa8WfSEXlLz3A0Pq1WQAKaPWz0YLMwwkX7HtctTJiu-3R2D5t5Yqn1Hl64SoXcvWSpVIFU6J8Chu6zaQRWxAmrt3hH~zhVw5QpS0~nfcxgRPw1fIFPicOKW7x20HJDuP5MEWsMEJvI2VK1~v02vU81XOrRn0adwmYrZh3dGlAsnXlGwcLVfoOuCmhJk8utFFot03~Q__>)
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
git clone https://github.com/PhiVault/BlueSheep.git
cd bluesheep
chmod +x bluesheep.sh
./bluesheep.sh
