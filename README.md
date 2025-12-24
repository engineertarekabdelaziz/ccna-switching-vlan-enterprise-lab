# ccna-switching-vlan-enterprise-lab
Enterprise-grade switching and VLAN design lab focused on CCNA concepts, including secure access, trunking, and network segmentation.
# Enterprise Switching Design Project

## 📌 Project Overview

This project demonstrates a **professional enterprise Layer 2 switching design** built using Cisco technologies and implemented in **Cisco Packet Tracer**. It focuses on **network segmentation, security, and manageability**, following best practices commonly required in corporate environments.

The project is designed to be **HR-friendly**, **interview-ready**, and **technically solid**, showcasing real-world skills expected from a **Network / Infrastructure Engineer**.

---

## 🎯 Objectives

* Design a scalable and secure **Layer 2 enterprise switching architecture**
* Implement **VLAN-based network segmentation**
* Apply **Port Security** to mitigate unauthorized access
* Enable **secure remote management using SSH**
* Follow clean documentation and naming conventions

---

## 🏗️ Network Architecture

**Network Model:** Hierarchical Design

* **Access Layer:** End-user connectivity
* **Distribution Layer:** VLAN routing & policy control

**Devices Used:**

* Cisco 2960 Switches
* End devices (PCs)

---

## 🧩 VLAN Design

| VLAN ID | Name       | Department         | Subnet          |
| ------- | ---------- | ------------------ | --------------- |
| 10      | Admin      | Administration     | 192.168.10.0/24 |
| 20      | IT         | IT Department      | 192.168.20.0/24 |
| 30      | Sales      | Sales Department   | 192.168.30.0/24 |
| 40      | Management | Network Management | 192.168.40.0/24 |

Each VLAN is logically isolated to improve **security, performance, and fault containment**.

---

## 🔐 Security Implementation

* **Port Security**

  * Sticky MAC Address
  * Limits unauthorized devices

* **Spanning Tree Enhancements**

  * PortFast
  * BPDU Guard

* **Management Security**

  * SSH v2 enabled
  * Local user authentication
  * Encrypted passwords

---

## 🌐 IP Addressing & Management

* Dedicated **Management VLAN (VLAN 40)**
* Each switch configured with:

  * IPv4 Management Address
  * IPv6 Addressing
  * Secure SSH Access

---

## 📂 Project Structure

```
Enterprise-Switching-Design/
│
├── README.md
├── diagrams/
│   └── network-topology.png
├── packet-tracer/
│   └── switching-project.pkt
├── configs/
│   └── switch-configs.txt
├── documentation/
│   └── vlan-design.md
```

---

## 🛠️ Tools & Technologies

* Cisco IOS
* Cisco Packet Tracer
* VLANs & Trunking
* SSH & Port Security
* IPv4 / IPv6

---

## 👤 Author

**Name:** Tarek Abdel Aziz
**Role:** Network & Systems Engineer
**Focus Areas:** Switching, Network Security, Infrastructure Design
