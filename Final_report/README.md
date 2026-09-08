## 3. Lab Environment

### Host System

- **Operating System:** Windows 11
- **Nmap:** Version 7.991, installed on Windows
- **Wireshark:** Installed on Windows
- **Virtualization Platform:** Oracle VirtualBox

### Virtual Machine – Authorized Target

- **Operating System:** Ubuntu Desktop
- **IP Address:** 192.168.56.101
- **Network Interface:** enp0s3
- **Network:** 192.168.56.0/24
- **Network Type:** VirtualBox Host-Only Adapter

### Network Configuration

The lab environment was configured using a **VirtualBox Host-Only network**, providing an isolated environment for security testing.

The Windows host was used to perform Nmap scans against the authorized Ubuntu target VM, while Wireshark was used to capture and analyze network traffic.

### Lab Network Overview

Windows 11 Host
      |
      | VirtualBox Host-Only Network
      | 192.168.56.0/24
      |
      └── Ubuntu Desktop VM
          IP: 192.168.56.101
          Interface: enp0s3
          Authorized Target
