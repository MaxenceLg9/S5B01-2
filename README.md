# Network Infrastructure Project - Nailloux

This repository contains the configurations and documentation for the Nailloux Photo Club network infrastructure project, including routing, DHCP, DNS, NAT/PAT, and security setups.

## IP Addressing
- **IPv4**: Addressing plan for all sites and VLANs.  
- **IPv6**: Dual-stack addressing plan.

## OSPF Configuration
- Installation and configuration of OSPF for intra-site routing.  
- OSPF configuration details for each router are included in `/configs/ospf/`.

## DHCP Setup
- **DHCPv4**: Server and client configurations, VLAN-specific ranges.  
- **DHCPv6**: Server setup, RA configuration on routers, and relay configuration.

## DNS
- Installation and configuration of Unbound for internal name resolution.  
- Integration with Nginx reverse proxy and Docker environment.

## Network Machines
- **Network VM**: Routing, firewall, NAT/PAT configurations.  
- **Application VM**: Service deployment, container configurations, `/etc/resolv.conf` updates.

## NAT/PAT
- IPv4 NAT/PAT

## BGP Configuration
- **IPv4 and IPv6**: Inter-site routing and external connectivity setup.

## ACLs
- Procedure for creating rules.  
- IPv4 and IPv6 rules for access control and security enforcement.

## Deployment
- Application and service deployment on the application VM.  
- Docker and container configurations for consistent environment setup.
