# kali-nmap-localhost-scan
First scan performed in a Kali Linux home lab environment using Nmap
# Kali Linux Nmap Localhost Scan

## Project Overview
This project demonstrates a basic network reconnaissance scan using Nmap within a Kali Linux virtual machine. The scan targets the local host (`127.0.0.1`) to identify open ports, services, and operating system details. This was performed as part of a cybersecurity home lab setup.

## Objective
The goal of this scan was to validate Nmap functionality, observe system response on a hardened machine (Kali), and practice standard scanning techniques used in vulnerability assessments and threat hunting.

## Tools Used
- Kali Linux 2025.1c (running in VirtualBox)
- Nmap 7.95

## Command Used
```bash
nmap -sV -O 127.0.0.1 -oN first-scan.txt
Results Summary
Host was reachable (127.0.0.1).

All 1000 common TCP ports were closed (reset).

No active services were detected.

OS detection was inconclusive due to multiple fingerprint matches.

These results are typical for a default installation of Kali Linux, which is designed to be hardened and minimal by default.

File Included
first-scan.txt: Raw output of the scan in plain text format.

Next Steps
This scan serves as a baseline for comparing scans of more vulnerable systems such as Metasploitable, which will be set up next in the lab
