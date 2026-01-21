# Malware
- Software that is intentionally designed to cause harm to systems, devices, networks, or users

## Ransomware
- Malware that takes over a computer and then demands a ransom
- Other techniques include: threatening to report user to law enforcement due to pirated software, expose sensitive info
- Significant portion of ransomware attacks are from phishing compaigns, some are from direct attack methods
- IOC's include:
    - C&C traffic and/or contact to known malicious IP addresses
    - Use of legitimate tools in abnormal ways to retain control of the compromised system
    - Lateral movement processes that seek to attack or gain info about other systems inside the same trust boundaries
    - Encryption of files
    - Notices to end users of the encryption process with demands for ransom
    - Data exfiltration behaviors
- Mitigation practice: effective backup system that will not be impacted if system or device it backs up is infected by ransomware

## Trojans
- Malware that is typically disguised as legitimate software
- Example: Triada Trojan: the guise is a feature-enhanced WhatsApp version
- When application is launched the Trojan gathers info about the devince and registers it with a remote server which allows futhur actions to take place
- Remote Acess Trojans (RATs): provide attackers with remote access to systems
- IOC's include:
    - Signatures for the specific malware apps or downloadable files
    - Command and control system hostnames and IP addresses
    - Folders or files created on target devices
- Mitigation practice: awareness practices, control software and applications that users can acquire, anti-malware and other tools to identify and stop trojans

- Side note: many types of malware use command and control (C&C) techniques to allow attackers to tell them what to do. These groups of systems under central command are botnets, individual systems are bots. C&C increasingly uses encrpyted HTTP connections
