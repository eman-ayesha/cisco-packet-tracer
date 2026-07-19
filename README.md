# Computer Networks Projects using Cisco Packet Tracer

## Project Overview

This repository contains three Computer Networks projects developed using **Cisco Packet Tracer**. The projects demonstrate fundamental networking concepts including **Internet of Things (IoT)**, **Dynamic Routing using RIP**, and **Inter-VLAN Routing**. These simulations provide hands-on experience with network design, device configuration, routing protocols, VLAN implementation, and smart device communication.

---

## Projects Included

### 1. IoT-Based Smart Home Network
**File:** `iot.pkt`

#### Description
This project simulates a Smart Home environment where IoT devices communicate through a Home Gateway. Users can remotely monitor and control smart appliances over the network.

#### Objectives
- Understand IoT architecture.
- Connect smart devices to a wireless network.
- Configure IoT devices and Home Gateway.
- Demonstrate remote monitoring and automation.

#### Components Used
- Home Gateway
- Wireless Router
- PC/Laptop
- Smartphone
- Smart Light
- Smart Fan
- Smart Door
- Temperature Sensor
- Smoke Detector

#### Working
1. The Home Gateway provides wireless connectivity.
2. IoT devices register with the gateway.
3. Devices obtain IP addresses automatically through DHCP.
4. Users log into the gateway or IoT server.
5. Sensor data is transmitted continuously.
6. Users can remotely control connected devices.
7. Automation rules perform actions based on sensor conditions.

#### Applications
- Smart Homes
- Smart Offices
- Healthcare Monitoring
- Industrial Automation

---

### 2. Dynamic Routing using RIP
**File:** `rip.pkt`

#### Description
This project demonstrates the implementation of the **Routing Information Protocol (RIP Version 2)** for dynamic routing between multiple networks.

#### Objectives
- Configure dynamic routing.
- Enable communication between different LANs.
- Learn routing table exchange.
- Understand hop-count based routing.

#### Components Used
- Cisco Routers
- Cisco Switches
- PCs
- Ethernet Cables

#### Working
1. IP addresses are assigned to router interfaces.
2. RIP Version 2 is configured on each router.
3. Routers advertise their directly connected networks.
4. Routing updates are exchanged periodically.
5. Routing tables are built automatically.
6. Packets are forwarded using the shortest path determined by hop count.

#### Features
- Dynamic route learning
- Automatic routing updates
- Reduced manual configuration
- Classless routing support

#### Limitations
- Maximum hop count of 15
- Slow convergence
- Suitable mainly for small and medium-sized networks

---

### 3. Inter-VLAN Routing
**File:** `intervlan.pkt`

#### Description
This project demonstrates communication between multiple VLANs using the **Router-on-a-Stick** technique.

#### Objectives
- Create VLANs.
- Configure trunk links.
- Implement Inter-VLAN Routing.
- Enable communication between separate VLANs.

#### Components Used
- Cisco Router
- Cisco Switch
- PCs
- Ethernet Cables

#### VLANs Configured
- VLAN 10
- VLAN 20
- VLAN 30

#### Working
1. VLANs are created on the switch.
2. Switch ports are assigned to the appropriate VLANs.
3. A trunk connection is established between the switch and router.
4. Router subinterfaces are configured using IEEE 802.1Q encapsulation.
5. Each subinterface acts as the default gateway for its VLAN.
6. Devices within the same VLAN communicate directly.
7. Communication between different VLANs is performed by the router.

#### Features
- Network segmentation
- Reduced broadcast traffic
- Improved security
- Efficient network management

---

## Software Used

- Cisco Packet Tracer
- Cisco IOS CLI

---

## Learning Outcomes

After completing these projects, the following networking concepts were understood and implemented:

- IP Addressing
- Network Device Configuration
- VLAN Configuration
- Trunking
- Router-on-a-Stick
- Dynamic Routing (RIP Version 2)
- Routing Tables
- IoT Device Configuration
- DHCP
- Wireless Networking
- Remote Device Management
- Network Troubleshooting

---

## Repository Structure

```
Computer-Networks-Projects/
│
├── iot.pkt
├── rip.pkt
├── intervlan.pkt
└── README.md
```

---

## Requirements

- Cisco Packet Tracer (version 8.0 or later recommended)
- Basic understanding of Computer Networks
- Knowledge of Cisco IOS commands

---

## Conclusion

These projects demonstrate practical implementations of fundamental networking concepts using Cisco Packet Tracer. Together, they provide experience with smart networking technologies, dynamic routing protocols, and VLAN-based network segmentation. The repository serves as a learning resource for students studying Computer Networks and preparing for networking labs, practical exams, and real-world networking scenarios.


**Course:** Computer Networks  
**Tool Used:** Cisco Packet Tracer
