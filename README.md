Enterprise Network Design using Cisco Packet Tracer

Project Overview

This project focuses on designing and configuring an enterprise network using Cisco Packet Tracer. It demonstrates fundamental networking concepts, network segmentation, routing, redundancy, and security.

Technologies and Tools

- Cisco Packet Tracer
- Cisco IOS CLI
- VLANs and trunking
- Router-on-a-stick inter-VLAN routing
- Spanning Tree Protocol (STP)
- Extended Access Control Lists (ACLs)
- DHCP
- NAT/PAT
- Switch Port Security

Network Features

1. VLAN Configuration
Created separate VLANs for HR, IT, Finance, and Servers to logically segment the enterprise network.

2. Inter-VLAN Routing
Configured router subinterfaces to enable communication between VLANs.

3. Switching and Redundancy
Connected multiple switches using trunk links and configured STP to manage redundant paths.

4. Network Access Control
Implemented an ACL to block traffic from the Finance subnet to the Company Server while permitting other IP traffic according to the configured policy.

5. DHCP
Configured DHCP pools on the router to assign IP addresses automatically to network devices.

6. NAT/PAT and External Network
Configured NAT/PAT and a simulated ISP connection to support communication with an external network. Final NAT translation and connectivity verification is still to be documented.

7. Switch Port Security
Configured port security on selected access ports using sticky MAC learning and the restrict violation mode.

VLAN and IP Addressing Plan

| VLAN | Department | Network         |
|------|------------|-----------------|
| 10   | HR         | 192.168.10.0/24 |
| 20   | IT         | 192.168.20.0/24 |
| 30   | Finance    | 192.168.30.0/24 |
| 40   | Servers    | 192.168.40.0/24 |

Files Included

- Enterprise_Network_Final.pkt — Packet Tracer network simulation
- screenshots — Network topology and configuration evidence

Learning Outcomes

- Practical experience with VLANs and inter-VLAN routing
- Understanding of STP and redundant switching paths
- Implementing ACL-based network access restrictions
- Configuring DHCP and NAT/PAT
- Applying basic switch port security
- Testing and troubleshooting a multi-switch enterprise network

How to Use

1. Install Cisco Packet Tracer.
2. Download the `.pkt` file from this repository.
3. Open the file in Packet Tracer.
4. Inspect the topology and device configurations.

Project Status

The main network configuration stages have been completed. Final connectivity and NAT verification should be checked against the included test evidence.

Author

IT Undergraduate | Networking and Infrastructure
