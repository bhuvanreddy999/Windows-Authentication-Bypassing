# Windows Authentication Bypassing  
**Tools:** Rufus 3.18, Windows PE, Hiren’s BootCD  
**Category:** Offensive Security / System Exploitation  

## 🔍 Project Overview
This project focuses on demonstrating multiple authentication bypass techniques on Windows 10/11 test machines using bootable tools and recovery environments. The goal was to reset or manipulate Windows authentication components to gain offline access without valid credentials.

## 🛠️ Tools & Technologies
- **Rufus 3.18**
- **Windows PE (WinPE)**
- **Hiren’s BootCD PE**
- NTFS Access Utilities  
- Command-line recovery tools

## 🚀 Methods Implemented
- Bypassed authentication on **90% of Windows 10/11 targets** in a controlled lab.
- Utilized bootable media to access system partitions and reset credential-related files.
- Demonstrated **3+ attack vectors**, including:
  - SAM database manipulation  
  - Offline registry editing  
  - Administrator password reset utilities  
  - Disabling authentication policies  

## 📄 Key Outcomes
- Successfully accessed locked systems without credentials.
- Documented each bypass method with steps, screenshots, and mitigation strategies.

## 🛡️ Defensive Recommendations
- Enable full disk encryption (e.g., BitLocker)  
- Enforce BIOS/UEFI passwords  
- Disable boot from external devices  
- Use secure boot  
