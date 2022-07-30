# Windows Command Line Tools

What is an SMB Port? A Detailed Description of Ports 445 + 139

The SMB protocol, or Server Message Block Protocol, creates a connection where a user can access a remote server or machine to facilitate actions on said machine. Since the year 2000, Microsoft still operates SMB over port 445. Port 139 is used by SMB to communicate over NetBIOS. Since it's inception, SMB has developed its dialect to meet network and security requirements; versions include: SMB 1.0, Samba, CIFS, NQ, Netsmb, SMB 2.0, Tuxera SMB, Likewise, SMB 2.1, SMB 3.0, MoSMB, SMB 3.02, and SMB 3.1.1. While most exploits have been patched, SMB protocols can still become exploitable through open ports, also known as as wormable ports. The Infamous ransomware attack known as the WannaCry exploit used a transport mechanism that targeted older computers that used outdated SMB protocols. 

How  to keep ports 139 and 445 secure:
  - Enable a firewall protection of these ports
  - Encrypt network traffic through a VPN
  - Use VLANS on private networks 
  - Use MAC address filtering
