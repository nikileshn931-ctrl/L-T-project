Applied Industrial Internet of Things
Configuration of Address Resolution Protocol (ARP)

Aim
To construct a simple Local Area Network (LAN) and understand the concept and operation of Address Resolution Protocol (ARP) using Cisco Packet Tracer by interconnecting PCs through an 8-port switch and LAN cables.

Problem Statement
In a computer network, devices communicate using IP addresses at the Network Layer and MAC addresses at the Data Link Layer. For successful communication, IP addresses need to be mapped to corresponding MAC addresses. This mapping is achieved using the Address Resolution Protocol (ARP).
The challenge is to simulate a LAN setup in Cisco Packet Tracer and demonstrate the working of ARP, showing how devices resolve IP addresses into MAC addresses during communication.

Scope of the Solution
•	Demonstrates the working of ARP in a LAN environment.
•	Provides hands-on understanding of how network devices exchange ARP requests and replies.
•	Useful for students and professionals learning networking concepts like IP-to-MAC mapping, ARP tables, and troubleshooting connectivity issues.
•	Can be scaled to larger networks with routers, servers, and multiple switches to understand ARP in more complex topologies.

Required Components
Software/IDE:
•	Cisco Packet Tracer
Hardware (Simulated in Packet Tracer):
•	1 × 8-port Switch
•	4 × PCs (or more as per design)
•	Straight-through LAN cables

Network Configuration
Each PC is assigned a unique IP address within the same subnet:
Device	IP Address	Subnet Mask	Default Gateway
PC0	192.168.1.1	255.255.255.0	192.168.1.254
PC1	192.168.1.2	255.255.255.0	192.168.1.254
PC2	192.168.1.3	255.255.255.0	192.168.1.254
PC3	192.168.1.4	255.255.255.0	192.168.1.254

Simulated Circuit
•	A LAN setup is created using 4 PCs connected to an 8-port switch with straight-through cables.
•	Each PC is configured with the above IP addresses.
•	ARP requests and replies are observed using Packet Tracer’s simulation mode to verify IP-to-MAC resolution.
•	The ARP tables of PCs are checked before and after communication to confirm the working of ARP.

Image
![simulation iot](https://github.com/user-attachments/assets/04a7c547-02a0-413d-9696-4bd499023588)




 
