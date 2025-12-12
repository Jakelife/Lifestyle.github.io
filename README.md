This comprehensive lab documentation demonstrates practical mastery of network reconnaissance and packet analysis through hands-on exercises with Nmap and Scapy, covering essential cybersecurity skills from host discovery and service enumeration to custom packet crafting and traffic analysis within a controlled internal environment.
                           
                            
                              (CONCISE)
The lab environment utilized Kali Linux with Nmap, Scapy, and tcpdump to analyze the 10.6.6.0/24 network range, specifically targeting host 10.6.6.23 through the br-internal/eth0 interface within ParoCyber's internal training infrastructure.

NMAP DOCUMENTATION 

1.HOST DISCOVERY


<img width="379" height="137" alt="Screenshot 2025-10-06 173725" src="https://github.com/user-attachments/assets/8787d571-0170-4095-a0fb-d70e99a16401" />


#This is useful for quickly discovering what devices are active on a network without the time overhead of port scanning. 

2.NMAP VERSION 

<img width="643" height="134" alt="Screenshot 2025-12-12 021407" src="https://github.com/user-attachments/assets/f6ebefe0-502a-4ffe-b2da-d4f9d6fa4723" />


#version of nmap


3.OPERATING SYSTEM DETECTION 

<img width="1150" height="284" alt="image" src="https://github.com/user-attachments/assets/c37018c1-a51d-4adf-8f3d-40f7ea7075d2" />

#Operating System fingerprints detection

4.PORT 21 AGGRESIVE SCAN

<img width="1225" height="374" alt="image" src="https://github.com/user-attachments/assets/c1b82224-7ed2-49d6-bba4-df80829b6005" />


#This scans the FTP port to identify the service version, OS,with aggresive and runs default scripts against the target.

5. SMB PORT SCAN

   <img width="1919" height="345" alt="image" src="https://github.com/user-attachments/assets/3c9164ff-1c99-45f2-a7ac-3bce7952560f" />


#Performs an aggressive scan on SMB/NetBIOS ports of host 10.6.6.23

6.SMB SHARE ENUMERATION WITH NSE SCRIPT

<img width="613" height="59" alt="image" src="https://github.com/user-attachments/assets/bb414f85-41a5-4012-a5a8-80afc8e8c496" />

#Enumerates SMB shares on the target OS

7. NMAP SCRIPT HELP

   <img width="1919" height="841" alt="image" src="https://github.com/user-attachments/assets/10e06ca1-400a-4333-a4a8-06bc9eb2395d" />

#Displays help information for all available NSE (Nmap Scripting Engine) scripts.

8.NETWORK COMMAND 

<img width="499" height="43" alt="image" src="https://github.com/user-attachments/assets/96a82700-0978-4947-9052-c1826966df2d" />

#Displays and configures network interface information on Linux/Unix systems.

9.NETWORK COMMAND(IP ROUTE)

<img width="634" height="103" alt="image" src="https://github.com/user-attachments/assets/7c0520f6-35e7-4966-a135-9a0abc3e0462" />

#Displays the system's routing table, showing how network traffic is directed.

10.DOMAIN NAME SYSTEM

<img width="640" height="93" alt="image" src="https://github.com/user-attachments/assets/286f6e47-eec3-49f3-9151-650207bf680f" />

#Troubleshooting DNS issues, verifying which DNS servers the system uses, checking network configuration during penetration testing or system administration.

11.PACKET CAPTURE WITH TCPDUMP

<img width="930" height="100" alt="image" src="https://github.com/user-attachments/assets/785f12c1-0ce4-4eb3-8d9e-1a58ba8ab9ed" />

#Captures all network traffic on interface eth0 and saves it to a file for later analysis.




SCAPY DOCUMENTATION 

1.STARTING SCAPY AS ROOT

<img width="739" height="403" alt="image" src="https://github.com/user-attachments/assets/f7a71606-4e08-40c3-9786-8681327fe259" />

#Interactive packet manipulation program used for network testing, packet crafting, scanning, and security research.


2. LIST OF FILES IN SCAPY

 <img width="1225" height="865" alt="image" src="https://github.com/user-attachments/assets/f43d759b-72b3-45dd-a8b3-b2ce7216c7f8" />

 #Lists available protocols and packet layers in Scapy.

 3.SCAPY IP LAYER

 <img width="832" height="269" alt="image" src="https://github.com/user-attachments/assets/afad9b58-51fd-47bd-a91e-30b7e50b6374" />

 #Displays detailed information about the IP (Internet Protocol) layer structure

4.BASIC PACKET SNIFFING 

<img width="382" height="47" alt="image" src="https://github.com/user-attachments/assets/b7c62cbf-198b-40d8-8daf-9c61d4e15045" />

#Intercepts and collects packets from a network interface for analysis or manipulation.

#PING COMMAND

 <img width="901" height="335" alt="image" src="https://github.com/user-attachments/assets/f80c9218-ae84-456b-a5cb-1b042c27c82c" />

#Sends ICMP Echo Request packets to check if a host is reachable and measures round-trip time (latency)

#STORE CAPTURED ICMP PACKETS

<img width="1057" height="508" alt="image" src="https://github.com/user-attachments/assets/afc85772-42fb-46cf-a4df-b355f6c4366b" />

#TRIGGER ICMP

<img width="398" height="67" alt="image" src="https://github.com/user-attachments/assets/aa6c9211-63ed-4754-9536-3d20949ef4ea" />






*SUMMARY OF THE WORK


The nmap component focused on active host discovery,os fingerprinting, comprehensive srevice enumeration, targeted SMB port scanning, and validation of SMBaccessibility. The Scapy component demostarted low-level packet analysis through pcket sniffing, interface-specific capture ICMP-based traffic filtering, and detailed packet inspection.
Collectively, these tasks reinforced core reconnaissance methodlogies and foundational packet-level analysis techniques that underpin real world penetration testing and cybersecurity operations  



THANK YOU




<img width="504" height="195" alt="fav-icon" src="https://github.com/user-attachments/assets/77d2bf33-6208-4e77-af15-2291cc47d81d" />








