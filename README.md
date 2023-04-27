**Practical-1**

AIM : Use Google and Whois for Reconnaisasance.

Theory :

Reconnaissance is a set of processes and techniques (Footprinting, Scanning & Enumeration) used to covertly discover and collect information about a target system.

Reconnaissance takes place in two parts − Active Reconnaissance and Passive Reconnaissance.
Active Reconnaissance
=====================
In this process, you will directly interact with the computer system to gain information. This information can be relevant and accurate. But there is a risk of getting detected if you are planning active reconnaissance without permission. If you are detected, then system admin can take severe action against you and trail your subsequent activities.

Passive Reconnaissance
======================
In this process, you will not be directly connected to a computer system. This process is used to gather essential information without ever interacting with the target systems.

Steps : 

You can get information about any website
by using the utility of "https://who.is" website.

This practical aim is to get information related about any website

**_practical 2_**

Aim : Use CryptTool to encrypt and decrypt passwords using RC4 algorithm.

Steps :

Download CryptTool : https://www.cryptool.org/ct1download/...

Install it by default options.

Run crypttool and remove all the default text from the window.

Now enter any text that you want to encrypt..

No go to encrypt/decrypt menu and then symmetric modern.. then select RC4..

The encrypted characters will be shown .. and 

similarly to decrypt that character again go to the encrypt/decrypt menu and 


Practical no.5

AIM : Using Nmap scanner to perform port scanning of various forms – ACK, SYN, FIN, NULL, XMAS.

Steps :
1) Download and Install Nmap. DL Link :  https://nmap.org/dist/nmap-7.70-setup...
2) Set path for nmap to access nmap from any window. (Follow me) put a semi colon and copy the location of nmaps directory..

Theory :

Open Zenmap GUI from desktop. then copy the commands and paste it in the text

•ACK -sA (TCP ACK scan)
It never determines open (or even open|filtered) ports. It is used to map out firewall rulesets, determining whether they are stateful or not and which ports are filtered.

Command: nmap -sA -T4 scanme.nmap.org

•SYN (Stealth) Scan (-sS)
SYN scan is the default and most popular scan option for good reason. It can be performed quickly, scanning thousands of ports per second on a fast network not hampered by intrusive firewalls.

Command: nmap -p22,113,139 scanme.nmap.org

•FIN Scan (-sF)
Sets just the TCP FIN bit.

Command: nmap -sF -T4 para (Not working)

•NULL Scan (-sN)
Does not set any bits (TCP flag header is 0)

Command: nmap –sN –p 22 scanme.nmap.org

•XMAS Scan (-sX)
Sets the FIN, PSH, and URG flags, lighting the packet up like a Christmas tree.

Command: nmap -sX -T4 scanme.nmap.org (Not working) :(

Thst it for this video.. Stay tuned..
AIM : Using Nmap scanner to perform port scanning of various forms – ACK, SYN, FIN, NULL, XMAS.

Steps :
1) Download and Install Nmap. DL Link :  https://nmap.org/dist/nmap-7.70-setup...
2) Set path for nmap to access nmap from any window. (Follow me) put a semi colon and copy the location of nmaps directory..

Theory :

Open Zenmap GUI from desktop. then copy the commands and paste it in the text

•ACK -sA (TCP ACK scan)
It never determines open (or even open|filtered) ports. It is used to map out firewall rulesets, determining whether they are stateful or not and which ports are filtered.

Command: nmap -sA -T4 scanme.nmap.org

•SYN (Stealth) Scan (-sS)
SYN scan is the default and most popular scan option for good reason. It can be performed quickly, scanning thousands of ports per second on a fast network not hampered by intrusive firewalls.

Command: nmap -p22,113,139 scanme.nmap.org

•FIN Scan (-sF)
Sets just the TCP FIN bit.

Command: nmap -sF -T4 para (Not working)

•NULL Scan (-sN)
Does not set any bits (TCP flag header is 0)

Command: nmap –sN –p 22 scanme.nmap.org

•XMAS Scan (-sX)
Sets the FIN, PSH, and URG flags, lighting the packet up like a Christmas tree.

Command: nmap -sX -T4 scanme.nmap.org (Not working) :(
