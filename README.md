# Networking Practice – Multi-Subnet Network Configuration

## Overview
This project focuses on the design and configuration of a small network infrastructure using Cisco Packet Tracer.

The objective was to establish communication between devices within the same network and across different subnets, while understanding the role of switches, routers, IP addressing, MAC addresses, and default gateways.

## Technologies Used
- Cisco Packet Tracer
- IPv4 Addressing
- Routing
- Switching
- ICMP (Ping)
- TCP/IP Networking
- OSI Model

## Network Topology

The network consists of:

- 1 Router
- 2 Switches
- 3 Devices in Subnet 1
- 2 Devices in Subnet 2

### Subnet 1
- Network: 192.168.100.0/24
- Gateway: 192.168.100.1

### Subnet 2
- Network: 192.168.200.0/24
- Gateway: 192.168.200.1

The router connects both networks and enables inter-subnet communication. :contentReference[oaicite:0]{index=0}

## Configuration Tasks

### IP Addressing
- Assigned static IPv4 addresses to all devices
- Configured subnet masks
- Configured default gateways

### Router Configuration
- Configured GigabitEthernet0/0 for Subnet 1
- Configured GigabitEthernet0/1 for Subnet 2
- Enabled communication between both networks

### Layer 2 & Layer 3 Analysis
- Examined MAC address usage at the Data Link Layer
- Analyzed IP addressing and routing at the Network Layer
- Studied packet forwarding through switches and routers

## Connectivity Verification

### Intra-Network Communication
- Successful ping tests between devices in the same subnet

### Inter-Network Communication
- Successful ping tests between devices located in different subnets
- Verified packet forwarding through the router

## Key Learning Outcomes

- IPv4 addressing and subnetting fundamentals
- Default gateway configuration
- Router-based inter-network communication
- MAC vs IP address functionality
- Switch and router operations
- OSI Layer 2 and Layer 3 concepts
- Network troubleshooting using ICMP ping

## Author

Nouman J Nizami – Network & Cybersecurity 
