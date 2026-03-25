# Multi-Building-Campus-Networking Project
This project demonstrates the design and implementation of a scalable multi-building campus network using core networking concepts. 
The network simulates a real-world university environment with multiple departments, centralized services, and inter-campus connectivity via WAN.
It was developed by first designing a structured network topology in Cisco Packet Tracer, dividing the campus into main and branch locations. VLANs were created on Layer 2 switches to logically separate departments such as Admin, HR, Finance, and IT, improving security and traffic management. 
Trunk links were configured between switches to allow VLAN traffic to pass across the network. 
A Layer 3 switch was then used to enable inter-VLAN routing by configuring Switch Virtual Interfaces (SVIs), allowing communication between different departments. 
DHCP was implemented on the router or Layer 3 switch to automatically assign IP addresses to devices within each VLAN. For inter-campus connectivity, routers were configured and connected via a WAN link using routing protocols or static routes to ensure seamless communication between campuses. 
Additionally, centralized servers were deployed to provide web, FTP, and email services, which were tested from different VLANs and locations. 
The network makes use of key components including servers, PCs, multilayer switches, and routers to ensure complete functionality.
The overall system was validated through successful ping tests, service accessibility, and end-to-end communication across the entire network.

