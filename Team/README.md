# Team | TryHackMe

## Room Information

* Platform: TryHackMe
* Room: Team
* Difficulty: Medium
* Category: Web Exploitation & Linux Privilege Escalation

## Overview

This room focused on web enumeration, Local File Inclusion (LFI), credential discovery, SSH access, command injection, and Linux privilege escalation.

The attack chain involved discovering a vulnerable development website, abusing an LFI vulnerability to access sensitive files, recovering an SSH private key, escalating privileges through command injection, and ultimately gaining root access through a vulnerable backup script executed by a cron job.

## Attack Path

```text
Virtual Host Enumeration
        ↓
LFI Discovery
        ↓
Source Code Disclosure
        ↓
FTP Credential Discovery
        ↓
FTP Access
        ↓
SSH Private Key Discovery
        ↓
SSH as dale
        ↓
Command Injection
        ↓
Privilege Escalation to gyles
        ↓
Cron Job Abuse
        ↓
SUID Bash
        ↓
Root
```

## Skills Learned

### Web Exploitation

* Virtual Host Enumeration
* Directory Enumeration
* Local File Inclusion (LFI)
* PHP Filter Abuse
* Source Code Disclosure

### System Enumeration

* FTP Enumeration
* SSH Enumeration
* User Enumeration

### Privilege Escalation

* Command Injection
* Sudo Misconfiguration Abuse
* Cron Job Abuse
* SUID Privilege Escalation

## Tools Used

* Nmap
* Gobuster
* Curl
* FTP
* SSH
* Linux Command Line


## Disclaimer

This writeup is intended for educational purposes and personal learning documentation. Flags, credentials, and sensitive information have been redacted where appropriate.
