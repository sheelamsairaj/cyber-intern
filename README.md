Task 1: Local Network Port Scan

Objective

The goal of this task was to learn how to discover open ports on devices in my local network using Nmap.

Tools Used

OS: Kali Linux (in a VMware VM)
Scanning Tool: Nmap
Process

I first identified my local network's IP range using the ip a command. My range was 192.168.140.0/24.
I then executed a TCP SYN scan with the command: sudo nmap -sS 192.168.140.0/24 -oN results.txt.
The scan identified 4 active devices on the network.
