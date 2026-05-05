# VLAN Segmentation with Router-on-a-Stick

Configured a multi-VLAN network using Router-on-a-Stick to enable inter-VLAN communication while maintaining logical segmentation and security.

## Overview
This lab simulates a small enterprise network with separate departments using VLANs, connected through a router for controlled communication.

## Network Design
- 1 Router (Cisco 2811)
- 2 Switches (Cisco 2960)
- 6 PCs

### VLAN Configuration
- VLAN 10 – Admin Department
- VLAN 20 – Sales Department

## Key Features Implemented
- VLAN creation and segmentation
- Static IP addressing (no DHCP)
- Trunking between switches
- Router-on-a-Stick configuration
- Inter-VLAN routing
- Switch port security

## Skills Demonstrated
- VLAN configuration and management
- Inter-VLAN routing
- Network segmentation
- Basic network security (port security)
- Troubleshooting connectivity issues

## Key Tasks
- Configured VLANs across multiple switches
- Established trunk links between switches and router
- Implemented subinterfaces on router for routing
- Assigned static IPs to all devices
- Enabled port security to restrict unauthorized access
- Verified connectivity using ICMP (ping)

## Result
Devices within the same VLAN communicated successfully, and inter-VLAN routing was achieved through the router while maintaining segmentation and basic security controls.
