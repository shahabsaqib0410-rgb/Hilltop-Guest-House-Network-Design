# Hilltop Guest House – Network Design and Implementation

## Project Overview
This project focuses on designing and implementing a small enterprise network for Hilltop Guest House using Cisco Packet Tracer.

The network is designed to separate departments through VLANs, implement efficient IP addressing using VLSM, and provide communication between different VLANs.

## Network Requirements

Three departments are included:

## Network Requirements

Three departments are included, each assigned a separate VLAN and subnet using VLSM.

| VLAN ID | Department | Network Address | Subnet Mask | Default Gateway | Usable IP Range | Broadcast Address |
|---|---|---|---|---|---|---|
| 10 | Guest | 192.168.100.0/26 | 255.255.255.192 | 192.168.100.1 | 192.168.100.2 – 192.168.100.62 | 192.168.100.63 |
| 20 | Staff | 192.168.100.64/27 | 255.255.255.224 | 192.168.100.65 | 192.168.100.66 – 192.168.100.94 | 192.168.100.95 |
| 30 | Management | 192.168.100.96/28 | 255.255.255.240 | 192.168.100.97 | 192.168.100.98 – 192.168.100.110 | 192.168.100.111 |


## Technologies and Concepts
- Cisco Packet Tracer
- VLAN Configuration
- VLSM Subnetting
- Inter-VLAN Routing
- Router-on-a-Stick
- Access and Trunk Ports
- IP Addressing
- Network Connectivity Testing

## Project Files
- Packet Tracer topology (.pkt)
- Network topology screenshots
- Configuration screenshots
- Ping and connectivity test results

## Learning Objectives
- Design a structured small enterprise network.
- Configure VLANs for departmental separation.
- Apply VLSM for efficient IP address allocation.
- Configure inter-VLAN communication.
- Test and troubleshoot network connectivity.

## Tools Used
Cisco Packet Tracer

## Author
Muhammad Saqib
## Network Topology
![Network Topology](Network%20Topology.png)

## VLAN Configuration
![VLAN Configuration](Vlans%20Configurations%20.png)

## Router Configuration
![Router Configuration](router%20configurations.png)

## Connectivity Testing
![Ping Results](ping%20result.png)
**Note:** This is a practical networking project. Configurations and testing evidence will be updated as implementation progresses.
