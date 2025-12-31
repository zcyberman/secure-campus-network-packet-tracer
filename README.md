# secure-campus-network-packet-tracer
Enterprise-style campus network designed in Cisco Packet Tracer featuring VLAN segmentation, inter-VLAN routing, DHCP, OSPF, NAT, wireless guest access, and layered security controls.


# Secure Campus Network – Cisco Packet Tracer

## Overview
This project simulates a small enterprise campus network designed and implemented in Cisco Packet Tracer. The network demonstrates VLAN segmentation, inter-VLAN routing using a multilayer switch, dynamic routing, DHCP services, wireless guest access, NAT, and layered security controls.

This repository represents an active, iterative build following real-world network design methodology.

## Network Topology
<img width="955" height="407" alt="image" src="https://github.com/user-attachments/assets/0fa87717-1b95-4103-bd2a-f49a9ea9dfb1" />


## VLAN Design
| VLAN ID | Name | Purpose |
|-------|------|--------|
| 10 | HR | Human Resources |
| 20 | IT | Information Technology |
| 30 | Finance | Finance Department |
| 40 | Guest | Guest Wireless Access |
| 99 | Management | Network Management |

## IP Addressing Plan
| VLAN | Subnet | Gateway |
|----|--------|--------|
| 10 | 192.168.10.0/24 | 192.168.10.1 |
| 20 | 192.168.20.0/24 | 192.168.20.1 |
| 30 | 192.168.30.0/24 | 192.168.30.1 |
| 40 | 192.168.40.0/24 | 192.168.40.1 |
| 99 | 192.168.99.0/24 | 192.168.99.1 |

## Current Status
 Physical topology complete  
 VLANs and trunking configured  
Inter-VLAN routing enabled (SVIs)

## Planned Enhancements
- DHCP server with per-VLAN scopes
- OSPF dynamic routing
- NAT for internet access
- Wireless guest network
- Access control lists (ACLs)
- Switch port security
- SSH management access

## Skills Demonstrated
- Cisco switching and routing
- VLAN segmentation and trunking
- Layer 3 switching (SVIs)
- Enterprise IP addressing design
- Network documentation
