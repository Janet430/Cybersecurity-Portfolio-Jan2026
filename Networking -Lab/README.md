NETWORKING LABS EXERCISES 
THIS FOLDER CONTAINS LABS AND DOCUMENTATION RELATED TO NETWORK MONITORING USING NMAP AND WIRESHARK  
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
   c. Differentiated between basic port scanning and vulnerability scanning using Nmap.[NMAP SCAN RESULT.pdf](https://github.com/user-attachments/files/24699105/NMAP.SCAN.RESULT.pdf)
   
   Tools used
   Kali-Linux
   Nmap

   NETWORK TRAFFIC MONITORING USING WIRESHARK
   
   To capture and analyze live network traffic in a controlled lab environment in order to understand network communication patterns and protocols.
   
   Methodology
a. Selected the active network interface on the lab machine.
b. Captured live traffic while interacting with web applications and network services.
c. Applied filters to analyze specific protocols such as HTTP, TCP, DNS, and TLS.

Observations
a. Multiple IP addresses were observed during the capture, including client and server systems.
b. HTTP and TCP traffic showed request–response communication patterns.
c. DNS queries were captured showing domain name resolution processes.

Key Learning
a. Learned how packet capture differs from active scanning.
b. Improved understanding of network protocols and traffic flow.
c. Gained experience using display filters to analyze captured packets.
Tools used
Wireshark
[NASITDEA ASSIGNMENT.pdf](https://github.com/user-attachments/files/24699058/NASITDEA.ASSIGNMENT.pdf)


NETWORK SERVICES – TRYHACKME

Completed hands-on lab exercises focused on enumerating and understanding common network services including SMB, Telnet and  FTP.

Key concepts learned include service discovery, authentication mechanisms, and common security risks associated with exposed network services. For ethical and policy reasons, detailed solutions and flags are not included.


