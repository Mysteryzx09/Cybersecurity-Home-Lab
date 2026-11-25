Cybersecurity Home Lab
This repository documents my cybersecurity learning journey using Kali Linux, VirtualBox, and various security tools.

Skills Being Developed
Linux Administration
Networking
Nmap
Wireshark
VirtualBox
Documentation
Cybersecurity Fundamentals
Lab 01 - Network Discovery with Nmap
Objective
Learn how to perform host discovery using Nmap and understand VirtualBox networking.

Environment
Host OS: Windows 11
Hypervisor: VirtualBox
Guest OS: Kali Linux
Tool Used: Nmap 7.99
Commands Used
ip addr
nmap -sn 10.0.2.0/24
Findings
Active hosts discovered:

10.0.2.2 (VirtualBox Gateway)
10.0.2.3 (VirtualBox DNS Service)
10.0.2.15 (Kali Linux VM)
What I Learned
How to identify a Linux system's IP address
How Nmap performs host discovery
How NAT networking works in VirtualBox
How to interpret scan results
Basic network enumeration concepts
Future Improvements
Build an Ubuntu target VM
Configure bridged networking
Learn Wireshark packet analysis
Perform service enumeration with Nmap

Troubleshooting: Initially Kali Linux was configured using VirtualBox NAT, which isolated the Virtual Machine from my home network. To provide full network visibility, I upgraded VirtualBox, repaired the networking components, and configured a Bridged Adapter using my Intel Wi-Fi adapter. After bridging, Kali received the IP address 192.168.12.106 from my home router. 
