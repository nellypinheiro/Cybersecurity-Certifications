# Active Directory Attacks CTF 1

**Platform:** INE  
**Certification Path:** eCPPT  
**Lab Type:** Capture the Flag (CTF)  
**Focus Area:** Active Directory Exploitation

---

## Overview

This lab focused on exploiting weaknesses in an Active Directory environment to gain unauthorized access, escalate privileges, and compromise domain infrastructure.

The objective was to identify misconfigurations and weak authentication mechanisms within the domain, including weak passwords, vulnerable Kerberos configurations, and credential exposure techniques. By leveraging password spraying, hash cracking, privilege enumeration, and Pass-the-Hash attacks, it was possible to move laterally across systems and gain access to the Domain Controller.

This lab simulated common attack paths used during real-world internal penetration tests against Active Directory environments.

---

## Skills Practiced

- Active Directory enumeration
- Password spraying attacks
- Kerberos pre-authentication abuse (AS-REP Roasting)
- Hash cracking
- Privilege enumeration within a domain
- Remote PowerShell sessions (PSSession)
- NTLM hash extraction
- Pass-the-Hash attacks
- Domain controller compromise

---

## Tools Used

- PowerShell
- DomainPasswordSpray.ps1
- PowerView.ps1
- Invoke-Mimikatz.ps1
- HFS (HTTP File Server)
- John the Ripper

---

## Lab Environment

**Attack Platform:** Windows machine joined to an Active Directory domain  

**Target Infrastructure:** Active Directory Domain Environment

---

## Key Learning Outcomes

- Identifying weak domain credentials through password spraying
- Exploiting accounts configured without Kerberos pre-authentication
- Cracking Kerberos hashes to recover plaintext credentials
- Enumerating domain privileges using PowerShell reconnaissance tools
- Establishing remote PowerShell sessions to compromised machines
- Extracting NTLM hashes from compromised hosts
- Performing Pass-the-Hash attacks to access privileged systems
- Compromising the Domain Controller

---

## Practical Attack Flow

1. Identify domain users with weak passwords using password spraying  
2. Authenticate to domain machines using compromised credentials  
3. Detect accounts configured without Kerberos preauthentication  
4. Perform AS-REP Roasting and crack the recovered hashes  
5. Enumerate administrative privileges across the domain  
6. Establish remote PowerShell sessions on vulnerable hosts  
7. Extract NTLM hashes from compromised systems  
8. Perform Pass-the-Hash attack to access the Domain Controller

---

## Completion Proof

Certificate of Completion issued by INE.  
See: `certificates/Certificate_of_Completion_AD-Attacks-CTF-1.pdf`
