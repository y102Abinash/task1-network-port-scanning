# task1-network-port-scanning
Performed a targeted port scan on a Metasploitable virtual machine using Nmap to identify open services and assess exposure. Task 1 of Elevate Labs Cybersecurity Internship.

# Task 1: Network Port Scanning 🔍

## 🎯 Objective
To perform a targeted port scan on a vulnerable machine (Metasploitable) in a local network and identify open services that may be potential security risks.

## 🛠️ Tools Used
- Nmap

## 🧪 Environment
- Attacking Machine: Kali Linux (or similar)
- Target Machine: Metasploitable VM
- Target IP: `192.168.64.134`

## 🧾 Steps Performed

1. Identified target IP: `192.168.64.134`
2. Performed a SYN scan using:
   ```bash
   nmap -sS 192.168.64.134
nmap -sS 192.168.64.134 -oN scan_results.txt


| Port | State | Service      |
| ---- | ----- | ------------ |
| 21   | open  | ftp          |
| 22   | open  | ssh          |
| 23   | open  | telnet       |
| 80   | open  | http         |
| 139  | open  | netbios-ssn  |
| 445  | open  | microsoft-ds |
| 3306 | open  | mysql        |
| 5432 | open  | postgresql   |


✅ Outcome
Learned to perform basic network reconnaissance.

Understood exposure risks via open ports.





