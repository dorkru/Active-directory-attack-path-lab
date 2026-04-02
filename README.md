# Active-directory-attack-path-lab
Active Directory attack path lab demonstrating domain compromise techniques (enumeration, credential access. lateral movement)
Active Directory Attack Path – Red Team Lab
Overview

This project demonstrates a simulated compromise of an Active Directory environment, starting from initial access to full domain compromise using common red team techniques.

Lab Environment
Windows Server (Domain Controller)
Windows 10 Client
Kali Linux
Tools: BloodHound, PowerView, Rubeus, Mimikatz, Impacket
Attack Path Summary
Initial access via compromised Windows client
Domain enumeration using PowerView and BloodHound
Identification of AS-REP roastable account
Credential extraction and password cracking
Lateral movement using PsExec
Privilege escalation to Domain Admin
Domain compromise and persistence (Golden Ticket)
Key Techniques
Active Directory enumeration
AS-REP Roasting
Credential dumping
Lateral movement
Golden Ticket attack
Key Takeaways
Misconfigurations in Active Directory can lead to full domain compromise
Attack paths are more important than single vulnerabilities
Proper monitoring and hardening can prevent most of these attacks
Disclaimer

This project was conducted in a controlled lab environment for educational purposes only.
