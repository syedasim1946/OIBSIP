# Task 1 - Basic Network Scanning with Nmap

## Objective
Perform a network scan using Nmap to identify open ports and services running on a target machine.

## Tools Used
- Nmap 7.99
- Windows

## Commands Used
- nmap 192.168.1.6
- nmap -sV 192.168.1.6

## Results

Open ports identified:

- 135/tcp - Microsoft Windows RPC
- 139/tcp - Microsoft Windows NetBIOS Session Service
- 445/tcp - Microsoft SMB File Sharing

## Findings

- Port 135 is used for Windows service communication.
- Port 139 is used for file and printer sharing.
- Port 445 is used by SMB for file sharing and network communication.

## Files Included

- nmap_scan_results.txt
- Scan screenshots

## Conclusion

The Nmap scan successfully identified open ports and services running on the target system.
