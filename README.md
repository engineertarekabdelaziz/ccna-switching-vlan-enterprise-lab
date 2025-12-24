# ccna-switching-vlan-enterprise-lab
Enterprise-grade switching and VLAN design lab focused on CCNA concepts, including secure access, trunking, and network segmentation.
# Enterprise Switching Design Project

## Project Overview

The Enterprise Switching Design Project is intended to show a professional layer 2 switching design for a corporation using Cisco products and Cisco Packet Tracer to implement the network. The enterprise switching design project is based on network segmentation, security, and manageability using industry standards typically required for corporations.

Project will be HR friendly, interview-ready, and technically sound for candidates to demonstrate their skills as required from a Network/Infrastructure Engineer position.

--

## Objectives

* Create a scalable and secure Layer 2 enterprise switching design (i.e., Architecture)
* Create a VLAN-based network segmented (segregated) architecture
* Utilize Port Security to help prevent unauthorized access to the network
* Provide secure remote management via SSH
* Follow clear documentation and naming conventions

--

## Network Architecture

**Network Model** - Hierarchical Design

* Access Layer (End-user connectivity)
* Distribution Layer (Routing and Policy Control by VLAN)

**Devices Used:**

* Cisco 2960 Switches
* End devices (PCs)

--

## VLAN Design

| VLAN ID | VLAN Name   | Department Name     | Subnet            |
| ------- | ----------- | ------------------- | ----------------- |
| 10      | Admin       | Administration      | 192.168.10.0/24   |
| 20      | IT          | IT Department       | 192.168.20.0/24   |
| 30      | Sales       | Sales Department    | 192.168.30.0/24   |
| 40      | Management  | Network Management   | 192.168.40.0/24   |

Each VLAN is logically segmented (or isolated) helping to provide Security, Performance, and Fault Containment.

--

## Security Implementation

* **Port Security**
   
   * Sticky MAC Address (prevents spoofing)
   * Limits devices that can attach to switch ports

* **STP Enhancements**
    
    * PortFast (Immediate transition to IPv4 or IPv6 forwarding)
    * BPDU Guard (Protects against loops)

* **Management Security**

     * SSH v2 enabled for secure remote access 
     * User Authentication via local user accounts
     * Encrypted passwords

--

## IP Addressing and Management

* Management VLAN (VLAN 40)
* Every switch has the following configuration parameters:

  * IPv4 Management Address
  * IPv6 Address
  * SSH Secure Remote Access 

--

## Project Directory Structure

```
Enterprise
