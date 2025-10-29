# computer_network_project




🚂 Railway Networking System Simulation

Course: CSE322 – Computer Networks Lab

This project is a detailed simulation of a reliable, secure, and efficient computer network designed for a modern railway platform and its administrative zones. Developed in Cisco Packet Tracer, the system demonstrates practical applications of network segmentation, diverse services (DHCP, DNS, HTTP), and robust routing to ensure seamless inter-departmental communication.

✨ Project Objectives & Features

The primary goal was to design a network mirroring real-world complexity and ensure functional, secure connectivity for all users and services.

Key Features Implemented:

Segmented Network Design: The entire network is logically divided into distinct zones to mimic real-world railway operations: Authority, Passenger, VIP Zone, and Platform.

VLSM Implementation: Variable Length Subnet Masking (VLSM) was used to efficiently segment the network (e.g., 192.168.10.0/24, 192.168.20.0/24, etc.) into smaller, manageable subnets, optimizing IP address usage and improving traffic control.

Core Network Services:

DHCP: Automatically assigns IP addresses to devices across multiple subnets.

DNS: Enables domain resolution for internal services, such as www.railwayportal.com.

HTTP: Hosts simulated internal web applications, including a Daily Train Schedule and a Ticket Booking System interface.

Secure Connectivity: Wireless access points (for Passenger and VIP zones) are secured using WPA2 encryption.

Static Routing: Static routes were configured between routers to ensure secure and documented connectivity, specifically addressing challenges encountered during routing configuration.

Comprehensive Testing: Successful verification of inter-subnet communication (Ping Tests), DNS resolution, and web access across all zones.

💻 Network Topology Overview

The network topology leverages multiple routers, multilayer switches, and various end devices (PCs, smartphones, servers) to simulate the required environment.

Tools and Technologies:

Simulation Tool: Cisco Packet Tracer

Devices: Cisco Routers, Multilayer Switches, Wireless Routers, DNS/HTTP Servers.

Protocols: DHCP, DNS, HTTP, Static Routing.

Security: WPA2.

Network Segmentation Example:

The design clearly separates mission-critical systems from public access points:

Zone (Subnet Example)

Function/Security Level

Authority (192.168.20.0/24)

High security, hosts DNS and HTTP servers.

Passenger (192.168.10.0/24)

General public access, DHCP enabled.

Platform/Ticket Gate (192.168.30.0/24)

Designated for information displays and gate control.

VIP Zone (192.168.40.0/24)

Higher privilege access, secured wireless.

(For the complete topology diagram and IP addressing scheme, please refer to the uploaded Packet Tracer file finalcnprojectwith_ticket.pkt.)

🚀 Future Enhancements

To further enhance the robustness and security of this railway network, the following improvements are planned:

VLAN Implementation: Implement Virtual Local Area Networks (VLANs) to ensure stronger broadcast domain separation and granular traffic control, moving beyond basic subnetting.

External Threat Protection: Introduce dedicated Firewalls to protect critical segments from external threats and manage traffic flow between the network and external connections.

Redundancy Protocols: Implement redundancy using protocols like HSRP (Hot Standby Router Protocol) to ensure high availability and prevent single points of failure for critical routing paths.

Advanced Monitoring: Integrate SNMP (Simple Network Management Protocol) for real-time monitoring and centralized management of all network devices.

Expanded Functionality: Integrate IP cameras for security surveillance and deploy VoIP (Voice over IP) services for internal staff communication.

👥 Team

This project was developed collaboratively by:

[Nazmul Islam Rahad] (ID: 0242310005101266)

