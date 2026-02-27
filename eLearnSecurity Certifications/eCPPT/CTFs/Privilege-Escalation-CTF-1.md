# Privilege Escalation CTF 1

**Platform:** INE  
**Certification Path:** eCPPT  
**Lab Type:** Capture the Flag (CTF)  
**Focus Area:** Privilege Escalation & Post-Exploitation  

---

## Overview
This Capture the Flag lab focused on exploiting stored credentials, analyzing system history, and leveraging vulnerable services to escalate privileges across multiple machines. The engagement simulated a realistic post-exploitation scenario involving credential harvesting, log analysis, lateral movement, and database extraction.

The objective was to capture all hidden flags by progressively escalating access from an initially compromised system to additional targets within the environment.

---

## Skills Practiced
- Credential harvesting from stored system data
- PowerShell history analysis
- Post-exploitation enumeration
- Service vulnerability exploitation
- Lateral movement between systems
- Database file extraction and credential recovery
- Privilege escalation to administrative/root level

---

## Tools Used
- PowerShell
- Firefox
- Nmap
- Metasploit Framework

---

## Lab Environment
**Attack Platform:**  
- Kali Linux (GUI)  
- Compromised Windows machine: `target1.ine.local`  

**Target Systems:**  
- `target1.ine.local`  
- `target2.ine.local`

---

## Key Learning Outcomes
- Identifying improperly stored credentials on compromised systems
- Extracting sensitive information from PowerShell command history
- Exploiting vulnerable services to gain shell access
- Recovering credentials from database files
- Escalating privileges across Windows and Linux environments
- Understanding real-world post-exploitation workflows

---

## Practical Attack Flow
1. Extract stored credentials from compromised Windows host  
2. Analyze PowerShell history for sensitive data exposure  
3. Exploit vulnerable services on a secondary target  
4. Retrieve database credentials for privilege escalation  
5. Obtain highest-level access and capture final flag  

---

## Completion Proof
Certificate of Completion issued by INE.  
See: `certificates/Certificate_of_Completion_Privilege-Escalation-CTF-1.pdf`
