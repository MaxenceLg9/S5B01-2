# Network Infrastructure Project - Nailloux

This repository contains the configurations and documentation for the Nailloux Photo Club network infrastructure project, including routing, DHCP, DNS, NAT/PAT, and security setups.

## IP Addressing
- **IPv4**: Addressing plan for all sites and VLANs. The configuration details for each router are included in `/Configurations/Routers' configurations/`,
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.
- **IPv6**: Dual-stack addressing plan. The configuration details for each router are included in `/Configurations/Routers' configurations/`,
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.

## OSPF Configuration
- Installation and configuration of OSPF for intra-site routing.  
- OSPF configuration details for each router are included in `/Configurations/Routers' configurations/`,
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.

## MPLS Configuration
- Installation and configuration of MPLS for intra-site routing.  
- MPLS configuration details for each router are included in `/Configurations/Routers' configurations/`,
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.

## DHCP Setup
- **DHCPv4**: Server and client configurations, VLAN-specific ranges.  
- **DHCPv6**: Server setup, RA configuration on routers, and relay configuration.
- The configuration file for the Network Server can be found in `/Configurations/Reseau/dhcpd.conf.txt`,
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.
- The configuration file for the distant router can be found in `/Configurations/Routers' configurations/logrt6.log`,
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.


## DNS
- Installation and configuration of Unbound for internal name resolution. The configuration file can be found in `/Configurations/Reseau/unbound.conf.txt`,
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.
- Integration with Nginx reverse proxy and Docker environment.

## Network Machines
- **Network VM**: Routing, firewall, NAT/PAT configurations.  
- **Application VM**: Service deployment, container configurations, `/etc/resolv.conf` updates.

## NAT/PAT
- IPv4 NAT/PAT

## BGP Configuration
- **IPv4 and IPv6**: Inter-site routing and external connectivity setup.
- The BGP configuration (including the BGP for MPLS) can be found in `/Configurations/Routers' configurations/`
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.

## ACLs
- Procedure for creating rules.  
- IPv4 and IPv6 rules for access control and security enforcement.
- The ACLs can be found on the router's configuration located in `/Configurations/Routers' configurations/`
or in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.

## Firewall
- Rules to monitor, filter, and control incoming and outgoing network traffic.
- The firewall rules can be found in the PDF file SAÉ_S5B01_Phase4_Equipe2.pdf.


## Deployment
- Application and service deployment on the application VM.  
- Docker and container configurations for consistent environment setup.
