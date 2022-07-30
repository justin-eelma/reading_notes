# Windows Command Line Tools

What is an SMB Port? A Detailed Description of Ports 445 + 139

The SMB protocol creates a connection where a user can access a remote server to facilitate actions on that machine remotely. Since the year 2000, Microsoft still operates SMB over port 445. Port 139 is used by SMB to communicate over NetBIOS. Since it's inception, SMB has developed its dialect to meet network and security requirements. Early SMB protocols were exploitable through open ports, known as wormable ports. The Infamous ransomware attack known as the WannaCry exploit used a transport mechanism that targeted older computers that used outdated SMB protocols. 

How  to keep ports 139 and 445 secure:
  - Enable a firewall protection of these ports
  - Encrypt network traffic through a VPN
  - Use VLANS on private networks 
  - Use MAC address filtering
