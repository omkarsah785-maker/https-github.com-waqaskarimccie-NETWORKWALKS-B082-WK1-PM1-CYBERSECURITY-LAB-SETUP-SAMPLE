# Cybersecurity Lab Setup

This repository contains the architecture, setup instructions, and configuration details for a virtualized network environment designed for ethical hacking, penetration testing, and security analysis.

---

## 🛠️ Environment Overview

The lab environment is built using Oracle VirtualBox and consists of virtual machine nodes configured across local and internal networks:

- **Windows 10 / Main Host OS**: Acts as the target host / workstation environment.
- **Kali Linux**: Acts as the security auditing and penetration testing platform.
- **VirtualBox Network Adapters**: NAT / Internal Network configuration to simulate real-world subnet isolation and communication.

---

## 📸 Setup Screenshots & Visual Guide

Here is a breakdown of the key screenshot references included in this project:

1. **`1-Screenshot-title-image.png`**: Main architecture diagram showing the overall VirtualBox lab structure, subnets, and host-guest topology.
2. **`2-screenshot-network-settings-1.png`**: Interface overview of the VirtualBox Manager highlighting virtual network adapter configurations.
3. **`3-screenshot-kali-linux.png`**: Active Kali Linux desktop environment window running inside the virtualization setup.
4. **`4-screenshot-kali-network-settings.png`**: Network configuration interface inside Kali Linux showing static/custom IP address assignment and subnet settings.

---

## ⚙️ Configuration Steps

1. **Virtual Machine Creation**: Provision Windows 10 and Kali Linux instances in VirtualBox.
2. **Network Interface Setup**: Configure proper network adapters (NAT / Internal Network / Host-Only) per VM.
3. **IP Configuration**: Assign and verify internal IP address bindings in Kali Linux to establish target communication.
