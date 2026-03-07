# Command & Control (C2/C&C) CTF 1

**Platform:** INE  
**Certification Path:** eCPPT  
**Lab Type:** Capture the Flag (CTF)  
**Focus Area:** Command & Control / Post-Exploitation

---

## Overview

This lab focused on establishing command and control (C2) over a compromised machine using PowerShell Empire. The objective was to exploit a vulnerable web application, gain initial access to the system, and maintain control of the compromised host.

Through a combination of reconnaissance, web exploitation, credential discovery, and privilege escalation, the attack progressed from initial access to full administrative control of the target machine.

This scenario simulated a typical red team post-exploitation workflow involving C2 infrastructure and lateral movement techniques.

---

## Skills Practiced

- Web reconnaissance
- Directory fuzzing
- Exploiting vulnerable web applications
- Establishing a C2 agent using PowerShell Empire
- Post-exploitation enumeration
- Credential discovery
- Privilege escalation on Windows systems
- Remote command execution

---

## Tools Used

- Nmap
- FFUF
- PowerShell Empire
- smbexec.py

---

## Lab Environment

**Attack Platform:** Kali Linux

**Target:**  
http://target.ine.local

---

## Key Learning Outcomes

- Discovering hidden directories using directory fuzzing
- Exploiting web functionality to upload malicious scripts
- Establishing a Command & Control agent using PowerShell Empire
- Maintaining persistence on a compromised Windows host
- Extracting stored credentials from the system
- Escalating privileges to obtain administrative access
- Navigating Windows directories to retrieve sensitive data

---

## Practical Attack Flow

1. Perform reconnaissance and identify hidden directories using fuzzing
2. Locate an exploitable path in the web application
3. Upload a malicious file (`update.bat`) to trigger code execution
4. Establish a C2 session with PowerShell Empire
5. Enumerate the compromised system
6. Identify stored credentials
7. Escalate privileges to Administrator
8. Retrieve the final flag from the Administrator directory

---

## Completion Proof

Certificate of Completion issued by INE.  
See: `certificates/Certificate_of_Completion_C2-CTF-1.pdf`
