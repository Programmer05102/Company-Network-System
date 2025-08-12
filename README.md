# 📡 Comprehensive Network Design for a Multi-Floor Company

## 📝 Project Overview

This repository contains a **Cisco Packet Tracer** simulation and configuration files for a **secure, scalable, and efficient network infrastructure** designed for a **three-story corporate building**.
The project integrates advanced networking devices, robust security measures, VLAN segmentation, and redundancy to ensure uninterrupted operations and future scalability.

---

## 🏢 Building Layout & Departments

The network connects multiple departments across three floors:

* **First Floor**

  * Sales Department
  * HR Department
* **Second Floor**

  * Finance Department
  * Admin Department
* **Third Floor**

  * ICT Department
  * Inside Server Department

Each department includes:

* 1 PC, 1 Laptop, 1 Tablet, 1 Smartphone
* 1 Printer
* 2 VoIP Phones
* 1 Cisco 2960 Switch

**Inside Server Department** includes:

* DNS Server
* DHCP Server
* Wireless LAN Controller (WLC-2504)
* Cisco 2811 Router
* Cisco 2960 Switch

---

## 🔧 Network Architecture

* **Core Backbone:** Two Cisco 3650-24PS multilayer switches
* **Security:** Dual Cisco 5506-X Firewalls with DMZ for external services (FTP, Web, Email servers)
* **Redundancy:** Dual Cisco 2911 Routers linked to cloud simulation
* **Routing Protocol:** OSPF for dynamic routing
* **VLANs:** Segmented for Management, LAN, WLAN, VoIP, Inside Servers
* **HSRP:** Hot Standby Routing Protocol for gateway redundancy

---

## 🔐 Security Features

* Firewall ACLs controlling inbound/outbound traffic
* NAT for internal-to-external communication
* DMZ for public-facing services
* PortFast & BPDU Guard for switch protection
* SSH access with password encryption

---

## 🖥 VoIP Configuration

* Configured VoIP network with dedicated VLAN
* DHCP pool for IP phones
* Auto-assigned extensions (401–410)

---

## 📂 Repository Contents

* `CN_PROJECT.pkt` – Cisco Packet Tracer simulation file
* `SETTINGS.txt` – Full CLI configuration for switches, routers, and firewalls
* `Project Report.pdf` – Detailed documentation including cost analysis, device list, and network design

---

## 💰 Cost Analysis (PKR)

| Category  | Cost          |
| --------- | ------------- |
| Hardware  | 6,430,000     |
| Cabling   | 250,000       |
| **Total** | **6,680,000** |

---

## 🚀 How to Use

1. Open `CN_PROJECT.pkt` in **Cisco Packet Tracer (v8.x or later)**
2. Refer to `SETTINGS.txt` for device configurations
3. Review `Project Report.pdf` for full network layout and cost breakdown

---

## 📜 Authors

* **Hisham Ahmed** (CSC-22S-052)
* Abdul Basit (CSC-22S-008)
* Abdul Ahad (CSC-22S-004)

Sindh Madressatul Islam University – BSCS – Computer Networks – Dec 2024

---

## 📄 License

This project is for **educational purposes** and may be used, modified, or referenced with proper credit.
