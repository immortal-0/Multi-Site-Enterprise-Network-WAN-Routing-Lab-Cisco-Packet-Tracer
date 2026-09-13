# Multi-Site-Enterprise-Network-WAN-Routing-Lab-Cisco-Packet-Tracer
Designed and configured a multi-site NJ–NY enterprise network using VLANs, SVIs, EtherChannel, VTP, static routing, DNS, HTTP services, and /30 WAN subnetting.
## Overview

This project demonstrates the design and configuration of a multi-site enterprise network connecting two locations: New Jersey and New York.

The network was built in Cisco Packet Tracer and includes multilayer switching, VLAN segmentation, inter-VLAN routing, EtherChannel, VTP, static routing, DNS, HTTP services, and point-to-point WAN connectivity.

## Technologies and Concepts

- VLANs
- Switched Virtual Interfaces (SVIs)
- Inter-VLAN Routing
- Layer 2 and Layer 3 Switching
- 802.1Q Trunking
- EtherChannel
- VTP
- Static Routing
- IPv4 Addressing
- /30 Point-to-Point Subnetting
- DNS
- HTTP
- Multi-Site Network Connectivity
- Network Troubleshooting

## Network Architecture

The topology contains two enterprise locations:

- New Jersey site
- New York site

Each site contains:

- Router
- Multilayer switch
- Layer 2 switch
- Multiple VLANs
- Client devices
- Web services

The NJ and NY routers are connected using a /30 point-to-point subnet.

## New Jersey Networks

VLAN 5:
192.168.0.0/30

VLAN 10:
10.0.0.0/24

VLAN 20:
10.0.1.0/24

## New York Networks

The New York site contains:

- VLAN 5 for routed connectivity
- VLAN 10 for application/web servers and selected clients
- VLAN 20 for additional client devices

SVIs were configured on the multilayer switch to provide routing between VLANs.

## Switching Configuration

- Configured VLANs on multilayer and Layer 2 switches
- Configured 802.1Q trunk links between switches
- Configured EtherChannel between switches
- Configured VTP for VLAN distribution
- Assigned endpoints to appropriate access VLANs

## Routing Configuration

- Enabled Layer 3 routing on multilayer switches
- Configured SVIs as VLAN gateways
- Configured static routes between switches and routers
- Created a /30 subnet for point-to-point communication between the NJ and NY routers
- Verified end-to-end connectivity between both sites

## Server Configuration

The environment includes multiple HTTP servers.

HTTP services were enabled and custom index pages were configured to identify individual applications.

DNS services were also configured to provide hostname resolution.
