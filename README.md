# Networking-2-Final-Project (Brewing Safe Connections: A Network Security Plan for a Coffee-Computer Shop)
Implementing a secure and segmented network for a small organization using VLANs, OSPF, DHCP, ACLs, and NAT.

## Overview
This simulation showcases a modernized network architecture across three subnets, featuring dynamic routing, secure remote access, proper segmentation, and centralized services such as DNS and DHCP. It improves scalability, performance, and overall network security.

### Key Configurations:
- VLAN Segmentation (Admin: VLAN10, Clients: VLAN20)
- Inter-VLAN Routing using router subinterfaces
- OSPF for dynamic routing across all routers
- DHCP for automated IP assignment per VLAN
- DNS Server for internal name resolution
- NAT for secure internet access via ISP router
- ACLs to control and filter traffic
- SSH for encrypted administrative access
