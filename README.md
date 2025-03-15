# BlueSheep 
Automatic Remote Malware Injection Tool ( Developed By Khusi-Docker & PhiVault )

![Screenshot 2025-03-07 001041.png](<https://media-hosting.imagekit.io//d57e78e3fb1549ec/Screenshot 2025-03-07 001041.png?Expires=1835894462&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=n0ANGmOpDv-BCZRUV94dymS5BkGAGH8fRFKpNephVUozAbvo65Xp6lqHPmbL5jE3pxu~W3NVTB-T9GPINuVHz3UQudwXwdwjMvRBxt0ce2nPTB-uR3RPBvvClz87x22bgfQCt8RIh99vVQqjrtc~fDl9uxTucMWnwYewyJjJOhCuXb~D7QhX3QfVtXqHm4w88RM7ldNeRBZhxaEfDk4i5dxrEXrx0sS6Ei8S4EiCBR3zP96NEa272q34A-kAd9KULrK8zpVQ~EPhb6rBexizsMCY1P98cDK59mjYdS0dPnxftWjKW2DKQEGNRjmCVMncsU7ie5cD1w~EHO8qUDem-Q__>)
## Overview  
BlueSheep is a remote system shutdown tool designed to *permanently disable* a vulnerable system until a new OS is installed. It operates using *Rainbow*, our custom-developed malware that automates the process, allowing a system to be taken down in minutes if vulnerabilities exist.  

![Screenshot 2025-03-15 110339.png](<https://media-hosting.imagekit.io//134e0e3159c84ef1/Screenshot 2025-03-15 110339.png?Expires=1836624919&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=YcEBm9tbILPV572KizlF~R26Xy67k6CjIw7eUP2AqBW0MC9x6w30Ri7BdLZ47xy6HcFi1FEVaZxL68ObPFEykpl1IjNGKRi9C7OlTac5Ae9zV9GDjqXWzQ7pRMBBkdzl3w~x0EgS6lGShuMxgx-rsOAd8v9fb3swFx9EK1TojpNaXGnYq59sBPy5DwI19wVuIUAT0~N~EhmFKkcdOy9RI-q-HlrNtEvglkrDx0RWLWG0CW63AgzLqqjq7aPEppr7GmdlGUM-Kn-D2Ok3mHVVr~Xn2PilTZQ5AZ1-cGOuPfPGmbRdXMbzARr5aVKX4dBb7Rs6-IgoPDZMqGeuzKdTZQ__>)

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
