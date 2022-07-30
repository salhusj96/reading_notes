# **Class 05 Reading Notes**
## **Server Message Block Protocol**

### *Why is this topic important?*
- The SMB Ports are one of the ways that computers talk to eachother, and it is imperative that we as Cybersecurity professionals understand how computers send/receive data between one another on a shared network. It is also imperative that we are aware of how these methods of communication between computers can quickly become a security risk.
---
### **How does it work?**
- SMB works through a client-server approach
  - A client makes a request, and the server responds accordingly
  - Response-request Protocol; facilitates file shares between networked computers
- Software applications that run on a NetBIOS session service locate and identify eachother via NetBIOS names over TCP port 139
### **What are the SMB Protocol dialects?**
- SMB protocol was created in the 1980s by IBM
  - Spawned the Common Internet File System (CIFS), a specific SMB implementation that enables file-sharing
- SMB Implementations
  - SMB 1.0
  - Samba
  - CIFS
  - NQ
  - Netsmb
  - SMB 2.0
  - Tuxera SMB
  - Likewise
  - SMB 2.1
  - SMB 3.0
  - MoSMB
  - SMB 3.02
  - SMB 3.1.1 (Most recent)
### **What are Ports 139 and 445?**
- Port 139 is used by SMB dialects that communicate over NetBIOS
  - Transport layer protocol designed to use in Windows OS over a network
- Port 445 is used by newer versions of SMB (post 2000) on top a TCP stack
  - Allows SMB to communicate over the internet
  - This means you can use IP addresses in order to use SMB like file sharing
### **Are Open Ports dangerous?**
- There are known issues with exposing these ports to the internet
  - Can become a security risk when service listening to the port is misconfigured, unpatched, bulnerable to exploits, or has poor network security rules
- Most dangerous open ports are wormable ports
  - Open by default in some OSs
  - Wormable ports are ports that are open to worms, a malicious type of software that self-replicates and infects other computers while remaining active on infected systems