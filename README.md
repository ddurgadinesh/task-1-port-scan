# Task 1 – Local Network Port Scan

## 🎯 Objective
To scan the local network and identify open ports using Nmap.

## 🛠 Tools Used
- Nmap
- Kali Linux

##  Command Used
```bash
sudo nmap -sS 10.0.2.0/24

Observations

Live Hosts Found: 3

Example Open Ports:

135/tcp → msrpc

445/tcp → microsoft-ds

2869/tcp → icslap

Risks of Open Ports

Open ports may expose services vulnerable to attacks.

Example: port 445 can be used in SMB attacks like WannaCry.

 Learnings

Learned to identify devices and open ports

Understood basics of port scanning using TCP SYN
