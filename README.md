# NT.local Homelab Projects

This repository documents hands-on infrastructure, networking, and cybersecurity lab projects built to simulate enterprise IT environments.

The lab includes Active Directory infrastructure, virtualization with Proxmox, network segmentation with a Palo Alto firewall, UniFi switching, and secure remote access using Tailscale.

---

## Lab Infrastructure
## Network Topology

```
Internet
   │
ISP Router
   │
Archer Router (192.168.0.0/24)
   │
Palo Alto PA-220 Firewall (192.168.10.0/24)
(Vlan 30 IoT Devices) (Vlan 40 Isolation) 
   │
UniFi XG Switch
   │
Proxmox Hypervisor (NT-HV01)
   │
Virtual Machines
 ├── NT-DC01 (Primary Domain Controller)
 ├── NT-DC02 (Secondary Domain Controller)
 ├── NT-DC03 (Additional Domain Controller)
 └── NT-FS01 (File Server)
```

Hypervisor
- Proxmox Virtualization

Servers
- NT-DC01
- NT-DC02
- NT-DC03
- NT-FS01

Networking
- Palo Alto PA-220 Firewall
- UniFi XG 8 Port Switch
- VLAN Segmentation

Remote Access
- Tailscale Zero Trust Network

---

## Projects

| Project | Description |
|-------|-------|
| Active Directory Lab | Multi-domain controller enterprise lab |
| Proxmox Virtualization | Virtual infrastructure for lab environment |
| Palo Alto VLAN Segmentation | Firewall rules and network segmentation |
| Tailscale Zero Trust | Secure remote access to lab infrastructure |
| UniFi Network Deployment | Switch configuration and VLAN architecture |

---

## Author

**Noah Threatt**

IT Infrastructure | Networking | Cybersecurity
