# Active Directory Infrastructure Lab

## Overview

This project documents the deployment of a multi-domain controller Active Directory environment built in a virtualized lab.

The lab simulates a small enterprise network using Windows Server 2022 domain controllers running on a Proxmox hypervisor.

## Lab Architecture

- Hypervisor: Proxmox
  - NT-HV01
- Domain Controllers:
  - NT-DC01
  - NT-DC02
  - NT-DC03
- File Server:
  - NT-FS01
- Network Segmentation via Palo Alto Firewall
- Secure remote administration via Tailscale

## Key Technologies

- Active Directory Domain Services
- Group Policy Management
- LAPS (Local Administrator Password Solution)
- BitLocker via GPO
- DNS and DHCP configuration

## Security Implementations

- Admin tiering model
- Baseline firewall GPO
- LAPS deployment
- Secure remote management with Tailscale

## Skills Demonstrated

- Windows Server administration
- Active Directory architecture
- Group Policy configuration
- Infrastructure security hardening
- Virtualized lab design
