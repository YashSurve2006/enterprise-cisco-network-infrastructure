# Enterprise Cisco Network Infrastructure

This project demonstrates the design and configuration of an enterprise-level Cisco network using multiple routers and switches in Cisco Packet Tracer.

The network implements VLAN segmentation, inter-VLAN routing using Router-on-a-Stick, dynamic routing using RIP v2, and DHCP services for automatic IP allocation.

This project simulates a real-world enterprise network infrastructure with structured IP addressing and proper subnet planning.


## Network Features

✔ Multiple Cisco Routers  
✔ Cisco Catalyst 2960 Switches  
✔ VLAN Segmentation  
✔ Router-on-a-Stick Inter-VLAN Routing  
✔ RIP v2 Dynamic Routing  
✔ DHCP Configuration  
✔ Structured IP Addressing  
✔ Subnet Planning  
✔ End-to-End Connectivity Testing  


## Network Topology

The network consists of:

- 4 Edge Routers
- 2 Core Routers
- Multiple Layer-2 Switches
- Multiple VLANs
- End Devices (PCs)

Routers are connected using point-to-point networks and configured with RIP v2 for automatic route exchange.

Each floor/network is segmented into VLANs and connected through Router-on-a-Stick configuration.

## VLAN Configuration

Example VLAN Structure:

| VLAN ID | Department |
|--------|-------------|
| VLAN 51-54 | Floor 1 Networks |
| VLAN 61-64 | Floor 2 Networks |
| VLAN 71-74 | Floor 3 Networks |
| VLAN 81-84 | Floor 4 Networks |
| VLAN 91-94 | Floor 5 Networks |

Each VLAN is assigned a separate subnet.


## Routing Protocol

### RIP Version 2

RIP v2 is used for dynamic routing between routers.

Features:

- Automatic route exchange
- Subnet support
- Simple configuration
- Scalable design


## DHCP Configuration

Each router provides DHCP services for its local VLANs.

DHCP automatically assigns:

- IP Address
- Subnet Mask
- Default Gateway


## IP Addressing

Structured subnet-based addressing scheme used.

Example:
10.0.0.0/30 → Router Links
192.168.X.0/24 → VLAN Networks



## Testing and Validation

The network was tested using:

- Ping Tests
- Inter-VLAN Communication
- DHCP Address Assignment
- Routing Table Verification

All VLANs successfully communicate across routers.

## Software Used

- Cisco Packet Tracer


## Skills Demonstrated

- Network Design
- VLAN Configuration
- Inter-VLAN Routing
- Router-on-a-Stick
- Dynamic Routing (RIP v2)
- DHCP Configuration
- Subnetting
- Troubleshooting


## How to Open

1. Install Cisco Packet Tracer
2. Open the `.pkt` file
3. Start simulation

## Author

Yash Surve  
Network Engineering & Software Development Student
