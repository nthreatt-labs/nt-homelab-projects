Internet
   │
  ISP
   │
Archer Router (192.168.0.0/24)
   │
Palo Alto PA-220 Firewall (192.168.10.0/24)
(VLan 30 IoT Devices) (VLan 40 Isolation)
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
