
# Links to CTF Resources

## Cryptography
### Explainers
- Explanation of various types of ciphers - [Cipher Machines](https://web.archive.org/web/20190223031910/http://ciphermachines.com/types.html)
- Bitwise/binary math operations - [Wikipedia!](https://en.wikipedia.org/wiki/Bitwise_operation)


### Steganography
- [Digital Invisible Ink Toolkit](http://diit.sourceforge.net/)- Commonly used tool for NCL Stego challenges
- [General methodology tutorial](https://medium.com/@FourOctets/ctf-tidbits-part-1-steganography-ea76cc526b40)
### General tools
- [DCode.fr Tool List](https://www.dcode.fr/tools-list)
- [Online Bitwise Calculator](https://www.miniwebtool.com/bitwise-calculator/)
### Base converter
- [ASCII to Hex](https://www.asciitohex.com/) - Super nice, has most encoding and bases in it
# General
- [RSA Math Explainer <word doc)](https://github.com/valinkrai/ctf-resources/blob/main/Cryptography_-_Decoding_6_Answer%20(RSA%20Math%20Tutorial).docx?raw=true)


## Binary Exploitation
- [x86 Assembly explanation](http://flint.cs.yale.edu/cs421/papers/x86-asm/asm.html)
- [Ghidra Reverse Engineering Framework](https://github.com/NationalSecurityAgency/ghidra)
- [Disabling ASLR for local binary exploitation](https://askubuntu.com/questions/318315/how-can-i-temporarily-disable-aslr-address-space-layout-randomization)


## Network Analysis
- Wireshark Filtering - [Display Filters](https://wiki.wireshark.org/DisplayFilters)
- Usefull for working with wireshark stuff in CLI - [Tshark stuff](https://osqa-ask.wireshark.org/questions/41439/tshark-fields)
- [Tool for pulling files out of Wireshark](https://www.netresec.com/index.ashx?page=NetworkMiner)

## Password Cracking
### Explainers
- [GPU Password Cracking Methodoloy](https://blog.netspi.com/gpu-password-cracking-building-a-better-methodology/)

### NTLM
- [Rainbow Tables with Ophcrack](https://danscourses.com/cracking-hashes-with-rainbow-tables-and-ophcrack/ )

### Hashcat
- [Hashcat GPU Password Cracking - Vs. LinkedIn Dump](https://web.archive.org/web/20190319145705/https://www.trustedsec.com/2016/06/introduction-gpu-password-cracking-owning-linkedin-password-dump/)
- [Attacking WPA with hashcat](https://hashcat.net/wiki/doku.php?id=cracking_wpawpa2)
### Wireless Exploitation
- [Aircrack for WEP](https://www.aircrack-ng.org/doku.php?id=aircrack-ng)

### Word Lists
- [WeakPass - big word list](https://weakpass.com/download)
- [crackstation - big word list](https://crackstation.net/buy-crackstation-wordlist-password-cracking-dictionary.htm)
- Helpful tutorial on using cewl to create custom word lists by scraping a web page [Creating custom word lists with cewl](https://null-byte.wonderhowto.com/how-to/hack-like-pro-crack-passwords-part-5-creating-custom-wordlist-with-cewl-0158855/)

### Tools
- [hashes.com - Super basic reverse hash checker, sometimes ends up with competition ones if people double check with its hashing tools](https://hashes.com/en/decrypt/hash)


## Log Analysis
### Awk
- [General Tutorial](https://www.tutorialspoint.com/awk/awk_basic_examples.htm)
- [Field Seperators](https://www.gnu.org/software/gawk/manual/html_node/Command-Line-Field-Separator.html)
- [Sum Counting column of numbers](http://www.commandlinefu.com/commands/view/1497/using-awk-to-sumcount-a-column-of-numbers)

### Sed
- [Replacing values](http://www.grymoire.com/Unix/Sed.html#uh-1)

### Regex (DO IT, LEARN IT, LOVE IT)
- [General Tutorial](https://www.regular-expressions.info/quickstart.html)
- Best of the testers imo, supports multiple feature sets/types [Regex101 tester](https://regex101.com/)

### Other
- [sort command](https://www.computerhope.com/unix/usort.htm)
- [counting recurring lines with sort+uniq](http://theunixtips.com/bash-count-number-of-recurrence-of-lines/)


## Web Exploitation
### SQL Injection
[Blind SQL Injection - OWASP](https://www.w3schools.com/sql/sql_injection.asp)
[Blind SQL Injection - W3 Schools](https://www.w3schools.com/sql/sql_injection.asp)

## Scanning
- [Tool for finding hidden files on web servers](https://github.com/hannob/snallygaster)

## General Links
- [Generally helpful wordlists, hashcat rules, virus sample, and so on. ***This will trigger your anti-virus***](https://github.com/danielmiessler/SecLists)
- [GTFO Bins](https://gtfobins.github.io/) - Tool for finding binaries on limited machines to do specific tasks, such as when vim or curl is missing, offers potential replacements or endaround ways to do the same basic task

- [My NCL Team Answer Proposal Template](https://docs.google.com/spreadsheets/d/1LVExf45fiCA5zo2tTZmQNcgpVBN8CTxCCCOM9t0rsfg/edit?usp=sharing) - This is just a Google Sheets template to be modified with the various categories. It's not super user friendly, but it basically just looks to see if there's multiple people coming to the same answer, which is especially useful for categories where answers can be ambiguous or easy to mess up. Usually we'd just wait until its green before submitting.

