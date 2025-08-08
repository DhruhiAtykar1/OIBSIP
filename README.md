# OIBSIP
Oasis Infobyte Security Analyst Internship

# Task 1: Basic Network Scanning with Nmap
# Objective: Perform a network scan to identify open ports and services using Nmap.
# Tools: Nmap

# Steps
1. Installed Nmap
2. Ran the scan on target IP `192.168.0.192` using:
nmap -sV 192.168.0.192 > nmap_scan_results.txt
3. Saved the output in `nmap_scan_results.txt` (Notepad)
4. Took screenshots of the output and analysed it. 

# Analysis:
Nmap scan report for IP (192.168.0.192)
Host is up (0.00087s latency).
Not shown: 996 closed tcp ports (reset)

# | PORT    | STATE | SERVICE       | VERSION                             |
# | 135/tcp | open  | msrpc         | Microsoft Windows RPC               |
# | 139/tcp | open  | netbios-ssn   | Microsoft Windows netbios-ssn       |
# | 445/tcp | open  | microsoft-ds? |                                     |
# | 3306/tcp| open  | mysql         | MySQL (unauthorized)                |
# Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

# Conclusion
The scan identified many open ports that are critical for network services and hence knowing these open ports helps in assessing security risks.
