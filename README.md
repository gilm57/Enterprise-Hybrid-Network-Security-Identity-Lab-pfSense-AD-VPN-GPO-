# pfSense-Firewall-WindowsServer-Win10-Lab

This lab demonstrates a full **network and Active Directory environment** with:

- pfSense firewall with VLANs, pfBlockerNG, OpenVPN, and DHCP Relay  
- Windows Server 2022 as Domain Controller with AD, DNS, DHCP, GPO, shared drives, and NPS (RADIUS)  
- Windows 10 domain-joined client with folder redirection, mapped drives, and VPN connectivity  

> NOTE! All IPs, domain names, and hostnames are placeholders for security.

## Table of Contents
1. [Lab Overview](#lab-overview)
2. [Network Diagram](#network-diagram)
3. [pfSense Configuration](#pfsense-configuration)
4. [Windows Server Setup](#windows-server-setup)
5. [Windows 10 Client](#windows-10-client)


## Lab Overview

| Component           | Hostname      | IP Address       | Role / Services                       |
|--------------------|--------------|----------------|--------------------------------------|
| Firewall           | pfSense      | 192.168.10.1   | VLANs, DHCP Relay, OpenVPN, pfBlockerNG |
| Domain Controller   | DC01         | 192.168.10.10  | AD DS, DNS, DHCP, GPO, Shared Drives, NPS |
| Windows 10 Client   | WIN10-CL01   | DHCP           | Domain-joined, mapped drives, VPN    |

