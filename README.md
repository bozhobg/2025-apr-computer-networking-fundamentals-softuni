# Computer Networking Fundamentals
### Course by [SoftUni](https://softuni.bg/trainings/4640/computer-networking-fundamentals-april-2025) part of [Computer Networking](https://softuni.bg/modules/24/java-db/1544) module

Course aims to introduce students to computer networks, their fundamental principles of operation and details about how they function. Begins with introduction to basic concepts and gradually delves into different networking protocols. Course is not vendor specific and focuses on industrial standards and open protocols. 

Grade: 6.00/6.00 

### Course Structure  

1. **Introduction to networks**
	- Basic Concepts: brief introduction to types of devices, networking topologies, protocols, types of media, traffic types
	- IP and MAC Addresses
	- OSI and TCP/IP Model: data flow, encapsulation/decapsulation
	- Introduction to Cisco Packet Tracer
2. **IP Addresses and Host-to-Host Communication - Part 1**
	- Binary, Decimal and Hexadecimal Numbers
	- IPv4 - Details: network address, subnet mask, broadcast address, first and last host address, total number of hosts
	- Host-to-Host Communication without Routers
	- The ARP table
	- Basic Connectivity Checks
	- The Command Line
3. **IP Addresses and Host-to-Host Communication - Part 1**
	- Host-to-host Communication with Routers
	- Switch MAC Address Table
	- Device Memory Components
	- Subnetting
	- Broadcast Domain
	- CIDR and VLSM
4. **Network Access, Security and VLANs**
	- Accessing Networking Devices: SSH and Telnet connectivity
	- Securing Network Device Access: securing vty, console access, password reset
	- Introduction to VLANs
	- VLAN Details: access (untagged) ports, trunk (tagged) ports, native vlan
5. **Layer 2 Redundancy - Spanning Tree Protocol**
	- Spanning Tree Protocol (STP): algorithm, root switch, root ports, designated ports
	- STP tie-breakers, BPDU, Bridge ID and Priority
	- Rapid STP (RSTP)
	- Per-VLAN STP plus (PVST+)
6. **IP Services and Basic Routing**
	- IP Services: DHCP and DNS
	- Introduction to Routing
	- Direct Routing
	- Inter-VLAN Routing
	- Static Routing
7. **Routing Demonstrations**
	- Static Routing
	- SVI, L2 vs L3 Interface
	- The rule of the Longest Match
8. **Dynamic Routing with OSPF**
	- Introduction to Dynamic Routing
	- OSPF Introduction
	- Single Area OSPF Configuration
	- Administrative Distance vs Rule of the Longest Match
9. **Building Lab with Physical Devices**
	- Demo setup: router 1 Mikrotik, switch 1 3COM, switch 2 Cisco, access point controller Ruckus 
	- 2 scenarios done on PCT (as closely as possible without using NAT and vlan networks routing not isolated through access lists). 		
	- Scenario 1: 2 separate VLANs routed through router on a stick to the outside world, DHCP server on switch and separate Web+DNS Server in one of the VLANs, wireless access through Wireless Controller - 2 separate SSID for each vlan
	- Scenrio 2: 2 separate VLAN networks routed through L3 switch, DHCP+Web+DNS Server on separate network, wireless access through Wireless Controller - 2 separate SSID for each vlan
10. **Exam Preparation**
	- Course summary
	- Example exam solution
