Networking labs exercises
This folder contains labs and documentation related to network monitoring using Wireshark and Nmap
1. BASIC NETWORK SCANNING WITH NMAP ON OWASPS BROKEN WEB APPLICATION
   Nmap was used to scanned a local network which the ip address was 192.168.64.80
   (nmap 192.168.64.80) I pasted this Ip address on kali linux to scan for open ports and services
a.	Open ports: 22, 80, 139, 143, 443, 445, 5001, 8080 and 8081.
b. services: SSH, Http, Netbios-ssn, Imap, Https, Microsoft-ds, Commplex-link, Http-proxy and Blackice-icecap.

2. IDENTIFYING VULNERABLE SERVICES 
   Nmap was used to scanned common vulnerabilities on OWASPS broken web application
   nmap --script vuln 192.168.64.80
   Description:This scan was conducted in a controlled lab environment to identify known vulnerabilities using Nmap’s vulnerability scripts. The scan checks running services against known security issues and CVEs.
   Results: The scan identified multiple security weaknesses related to service misconfigurations, SSL/TLS vulnerabilities, and outdated services    running on the target system.
   Key Learning
   a. Learned how Nmap NSE scripts can be used for vulnerability identification.
   b. Improved understanding of how vulnerabilities are mapped to known CVEs.
   c. Differentiated between basic port scanning and vulnerability scanning using Nmap.



