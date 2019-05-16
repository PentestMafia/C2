# day-to-day

<img width="650" src="https://raw.githubusercontent.com/e-anakein/praia_essential_commands/master/PirateBaypadded.jpg">

## Table of Contents
* [Enumeration](#enumeration)
* [Exploitation](#exploitation)
* [Password Attacks](#password-attacks)
* [Wordlists](#wordlists)
* [Privilege Escalation](#privilege-escalation)
* [Buffer Overflows and Exploits](#buffer-overflows-and-exploits)
* [OSCP Preparation](#oscp-preparation)

------

## Enumeration
### Web Discovery
* [Dirsearch - Web path scanner](https://github.com/maurosoria/dirsearch)
* [Gobuster - Directory/file & DNS busting tool written in Go](https://github.com/OJ/gobuster)
* [Wfuzz - Web application fuzzer](https://github.com/xmendez/wfuzz)

### SMB Enumeration
* [SMB Checklist](https://0xdf.gitlab.io/2018/12/02/pwk-notes-smb-enumeration-checklist-update1.html)


## Exploitation
#### Search
* [Google](https://www.google.com/)
* [Exploit Database - Exploits for Penetration Testers, Researchers, and ...](https://www.exploit-db.com/)

## Privilege Escalation
#### Linux Privilege Escalation
* [pspy - Monitor linux processes without root permissions](https://github.com/PentestMafia/pspy)
* [LinEnum - Scripted Local Linux Enumeration & Privilege Escalation Checks](https://github.com/PentestMafia/LinEnum)
* [linuxprivchecker.py -- a Linux Privilege Escalation Check Script](https://github.com/sleventyeleven/linuxprivchecker)
* [vector (getcap/setcap)](https://nxnjz.net/2018/08/an-interesting-privilege-escalation-vector-getcap/)
* [linux-exploit-suggester](https://github.com/mzet-/linux-exploit-suggester)
* [Checklist](https://github.com/PentestMafia/Checklists/blob/master/Linux-Privilege-Escalation.md)

#### Windows Privilege Escalation
* [PowerSploit - A PowerShell Post-Exploitation Framework](https://github.com/PowerShellMafia/PowerSploit)
* [Windows Kernel Exploits](https://github.com/PentestMafia/windows-kernel-exploits)
* [PayloadsAllTheThings - Windows - Privilege Escalation](https://github.com/PentestMafia/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Windows%20-%20Privilege%20Escalation.md)
* [Checklist](https://github.com/PentestMafia/Checklists/blob/master/Windows-Privilege-Escalation.md)

#### Standalone binaries for Linux/Windows
* [Impacket Static Binaries - Standalone binaries for Linux/Windows of Impacket's examples](https://github.com/PentestMafia/impacket_static_binaries)
* [Various nix tools built as statically-linked binaries](https://github.com/andrew-d/static-binaries)

## Password Attacks
#### Brute Force
* [Nmap Brute forcing Scripts](https://nmap.org/nsedoc/categories/brute.html)
* [John The Ripper - is a fast password cracker](https://github.com/magnumripper/JohnTheRipper)
* [Crunch - Wordlist Generator](https://github.com/jim3ma/crunch)
* [Hashcat -  World's fastest and most advanced password recovery utility](https://github.com/hashcat)

#### Extract
* [Mimikatz - to extract plaintexts passwords, hash, PIN code and kerberos tickets from memory](https://github.com/gentilkiwi/mimikatz)

## Wordlists
* [SecLists - It's a collection of multiple types of lists used during security assessments, collected in one place](https://github.com/danielmiessler/SecLists)

## Buffer Overflows and Exploits
#### Nmap Fuzzers
* [Nmap Fuzzer List](https://nmap.org/nsedoc/categories/fuzzer.html)

#### Stack Based Overflows
* [Exploit writing tutorial part 1 : Stack Based Overflows](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)

#### Mona
* [mona.py - the manual](https://www.corelan.be/index.php/2011/07/14/mona-py-the-manual/)

#### Debugger
* [.NET debugger and assembly editor](https://github.com/0xd4d/dnSpy)
* [Immunity Debugger](https://www.immunityinc.com/products/debugger/)
* [OllyDbg](http://www.ollydbg.de/)
* [Radare](https://rada.re/r/)

## OSCP Preparation
#### Writeups / Exploits / Training
* [Random Exploits](https://github.com/w4fz5uck5/3XPL01t5)
* [Stack practice](https://github.com/e-anakein/OSCP)
* [MiniShare 1.4.1 - Remote Buffer Overflow](https://e-anakein.github.io/minishare/1.4.1/-/remote/buffer/overflow/2019/01/06/bof-minishare.html)

#### Writeups / Guide
* [OSCP Survival Guide](https://github.com/wwong99/pentest-notes/blob/master/oscp_resources/OSCP-Survival-Guide.md)

#### OSCP labs to automate information gathering and service enumeration
* [Reconnoitre](https://github.com/codingo/Reconnoitre)
* [Vanquish](https://github.com/frizb/Vanquish)

#### Vulnhub - Machines similar to the PWK labs
* [Metasploitable3](https://github.com/rapid7/metasploitable3)
* [Kioptrix: Level 1 (#1)](https://www.vulnhub.com/entry/kioptrix-level-1-1,22/)
* [Kioptrix: Level 1.1 (#2)](https://www.vulnhub.com/entry/kioptrix-level-11-2,23/)
* [Kioptrix: Level 1.2 (#3)](https://www.vulnhub.com/entry/kioptrix-level-12-3,24/)
* [Kioptrix: Level 1.3 (#4)](https://www.vulnhub.com/entry/kioptrix-level-13-4,25/)
* [FristiLeaks: 1.3](https://www.vulnhub.com/entry/fristileaks-13,133/)
* [Stapler: 1](https://www.vulnhub.com/entry/stapler-1,150/)
* [PwnLab: init](https://www.vulnhub.com/entry/pwnlab-init,158/)
* [Tr0ll: 1](https://www.vulnhub.com/entry/tr0ll-1,100/)
* [Tr0ll: 2](https://www.vulnhub.com/entry/tr0ll-2,107/)
* [Kioptrix: 2014](https://www.vulnhub.com/entry/kioptrix-2014-5,62/)
* [Lord Of The Root: 1.0.1](https://www.vulnhub.com/entry/lord-of-the-root-101,129/)
* [Mr-Robot: 1](https://www.vulnhub.com/entry/mr-robot-1,151/)
* [HackLAB: Vulnix](https://www.vulnhub.com/entry/hacklab-vulnix,48/)
* [HackInOS](https://www.vulnhub.com/entry/hackinos-1,295/)
* [VulnOS: 2](https://www.vulnhub.com/entry/vulnos-2,147/)
* [SickOs: 1.2](https://www.vulnhub.com/entry/sickos-12,144/)
* [pWnOS: 2.0](https://www.vulnhub.com/entry/pwnos-20-pre-release,34/)
* [Temple of Doom](https://www.vulnhub.com/entry/temple-of-doom-1,243/)
* [SolidState](https://www.vulnhub.com/entry/solidstate-1,261/)
* [Vulnix](https://www.vulnhub.com/entry/hacklab-vulnix,48/)
* [Zico2](https://www.vulnhub.com/entry/zico2-1,210/)
* [Billu_b0x 2](https://www.vulnhub.com/entry/billu-b0x-2,238/)
* [SkyTower](https://www.vulnhub.com/entry/skytower-1,96/)
* [WinterMute](https://www.vulnhub.com/entry/wintermute-1,239/)

#### IppSec Videos - Machines Windows
* [CTF - Windows -Easy](https://www.youtube.com/watch?v=Rr6Oxrj2IjU&list=PLidcsTyj9JXL4Jv6u9qi8TcUgsNoKKHNn)
* [CTF -Windows - Medium](https://www.youtube.com/watch?v=J2unwbMQvUo&list=PLidcsTyj9JXI9E9dT1jgXxvTOi7Pq_2c5)
* [CTF - Windows - Hard](https://www.youtube.com/watch?v=ob9SgtFm6_g&list=PLidcsTyj9JXK2sdXaK5He4-Z8G0Ra-4u2)
* [CTF - Windows - Insane](https://www.youtube.com/watch?v=Bhh5yPHjwUY&list=PLidcsTyj9JXJSn8KxSr_-9eKEwxJJtf_x)

#### IppSec Videos - Machines Unix
* [CTF - Nix - Easy](https://www.youtube.com/watch?v=OGFTM_qvtVI&list=PLidcsTyj9JXJfpkDrttTdk1MNT6CDwVZF)
* [CTF - Nix - Medium](https://www.youtube.com/watch?v=yQgtDoCDAYk&list=PLidcsTyj9JXJKC2u55YVa5aMDBRXsawhr)
* [CTF - Nix - Hard](https://www.youtube.com/watch?v=RLvFwiDK_F8&list=PLidcsTyj9JXJlmHwZScT3He3rO4ni-xwH)
* [CTF - Nix - Insane](https://www.youtube.com/watch?v=Yp4oxoQIBAM&list=PLidcsTyj9JXLI9mAR4MPiL19hq5lpaYNd)


