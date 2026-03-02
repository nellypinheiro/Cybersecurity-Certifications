# Lateral Movement & Pivoting CTF 1

**Platform:** INE  
**Certification Path:** eCPPT  
**Lab Type:** Capture the Flag (CTF)  
**Focus Area:** Lateral Movement & Network Pivoting  

---

## Overview
This Capture the Flag lab focused on performing lateral movement and pivoting within a compromised network environment. The objective was to escalate access across multiple machines by leveraging weak credentials, exploiting exposed services, and reusing previously discovered authentication data.

The lab simulated a real-world internal network compromise scenario where an attacker progressively expands control by abusing trust relationships and misconfigurations across systems.

---

## Skills Practiced
- Enumeration of open network services
- Credential brute-forcing and password reuse attacks
- Database enumeration and credential extraction
- Exploitation of exposed internal services
- Hash-based authentication abuse
- Lateral movement across multiple hosts
- Network pivoting between segmented systems

---

## Tools Used
- Firefox
- Nmap
- Metasploit Framework
- SSH
- MySQL

---

## Lab Environment
**Attack Platform:** Kali Linux (GUI)  

**Target Systems:**  
- `target1.ine.local`  
- `target2.ine.local`  
- `target3.ine.local`  
- `target4.ine.local`  

**Useful Wordlists:**
- `/usr/share/metasploit-framework/data/wordlists/common_passwords.txt`
- `/usr/share/metasploit-framework/data/wordlists/common_users.txt`
- `/usr/share/metasploit-framework/data/wordlists/unix_passwords.txt`

---

## Key Learning Outcomes
- Identifying weak credentials exposed through open services
- Extracting hidden credentials from accessible databases
- Exploiting trust relationships between systems
- Obtaining administrative credentials through service misconfigurations
- Performing pivoting using harvested password hashes
- Expanding control across segmented internal networks

---

## Practical Attack Flow
1. Exploit weak credentials on the initial target  
2. Enumerate internal databases to uncover additional user data  
3. Abuse open services to escalate access to secondary hosts  
4. Extract administrative credentials from compromised systems  
5. Pivot using obtained hashes to compromise additional machines  

---

## Completion Proof
Certificate of Completion issued by INE.  
See: `certificates/Certificate_of_Completion_Lateral-Movement-Pivoting-CTF-1.pdf`
