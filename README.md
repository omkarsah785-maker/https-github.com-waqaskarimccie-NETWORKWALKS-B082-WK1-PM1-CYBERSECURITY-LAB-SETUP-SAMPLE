# Cybersecurity Lab Setup

A virtualized cybersecurity laboratory environment designed for hands-on network testing, packet analysis, and security experimentation using isolated virtual machine architecture.

---

## Executive Summary

* **Project Purpose:** Established a secure, isolated sandbox environment to practice network scanning, traffic analysis, and ethical security testing without impacting production networks.
* **Environment Specs:** Configured Oracle VirtualBox to host Kali Linux integrated with custom dual virtual network adapters (NAT and Host-Only modes).
* **Lab Capabilities:** Enables packet capturing, vulnerability assessments, network discovery, and safe exploitation exercises within a strictly controlled virtual perimeter.

---

## Network Architecture & Configuration

* **Hypervisor:** Oracle VirtualBox
* **Guest OS:** Kali Linux
* **Network Adapters:**
  * **Adapter 1 (NAT):** Provides outbound internet access for tool/package updates.
  * **Adapter 2 (Host-Only):** Establishes an isolated internal network segment between host and guest environments.

---

## Repository File Structure

* `1-screenshot-network-settings.png` — VirtualBox network interface configuration (NAT & Host-Only setups).
* `2-screenshot-kali-linux.png` — Operational Kali Linux desktop environment inside the hypervisor.
* `3-screenshot-kali-network-settings.png` — Active IP addressing and routing verification inside Kali terminal.
* `README.md` — Project overview and setup documentation.
*
