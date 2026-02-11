# Network Penetration Testing CTF 1

**Platform:** INE  
**Certification Path:** eCPPT  
**Lab Type:** Capture the Flag (CTF)  
**Focus Area:** Network Penetration Testing & Lateral Movement  

---

## Overview
This Capture the Flag lab focused on leveraging SNMP to extract sensitive information and establish an initial foothold on a target system. The engagement progressed through privilege escalation and pivoting techniques to compromise an additional machine that was not directly accessible from the attack platform.

The lab simulated a real-world multi-stage attack involving information disclosure, shell access, privilege escalation, internal pivoting, and exploitation of vulnerable applications.

---

## Skills Practiced
- SNMP enumeration and exploitation
- Identification of exposed credentials and sensitive shares
- Remote shell acquisition
- Windows privilege escalation
- Network pivoting
- Exploitation of internally exposed applications
- Linux privilege escalation via user misconfigurations

---

## Tools Used
- Metasploit Framework
- Proxychains
- Finger
- Nmap
- Python
- Firefox

---

## Lab Environment
**Attack Platform:** Kali Linux (GUI)  
**Target Systems:**  
- `server.prod.local`  
- `web.prod.local`

---

## Key Learning Outcomes
- Leveraging SNMP misconfigurations to extract sensitive user information
- Identifying access to exposed network shares
- Gaining remote shell access on Windows systems
- Performing privilege escalation to Administrator level
- Pivoting through compromised hosts to reach internal systems
- Exploiting vulnerable internal applications
- Analyzing user configuration files (e.g., .plan) for privilege escalation vectors

---

## Completion Proof
Certificate of Completion issued by INE.  
See: `certificates/Certificate_of_Completion_Network-Pentest-CTF-1.pdf`
