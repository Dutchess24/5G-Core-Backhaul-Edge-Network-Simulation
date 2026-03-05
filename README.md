# 5G-Core-Backhaul-Edge-Network-Simulation

This project simulates a simplified telecom network architecture using Cisco Packet Tracer.
The topology follows a typical **Core → Backhaul → Edge → Access** structure similar to modern 4G/5G infrastructure.

The goal of this project was to practice **IPv6 addressing, OSPF routing, and network segmentation** while demonstrating how different parts of a telecom network communicate.

---

## Network Topology

The network consists of four routers representing different layers of a telecom infrastructure:

* Core Router – Represents the central network responsible for routing traffic across the infrastructure.
* Backhaul Router – Connects the access network to the core.
* Edge Router – Interfaces with the access network and servers.
* gNode Router – Simulates the base station side of the network.

End devices include:

* PCs connected through VLANs
* A server providing network services

---

## Technologies Used

* Cisco Packet Tracer
* IPv6 Addressing
* OSPF Routing Protocol
* Router Subinterfaces
* VLAN segmentation
* End-to-End connectivity testing using ping and traceroute

---

## Key Configuration Features

### IPv6 Addressing

All devices were configured using IPv6 addressing to simulate modern telecom networks.

### OSPF Routing

OSPF was implemented to dynamically advertise routes between the routers.

### VLAN Subinterfaces

Router subinterfaces were configured to allow multiple networks to communicate through the edge router.

Example:

* `Gig0/0`
* `Gig0/0.10`
* `Gig0/0.20`

---

## Network Testing

The following tests were performed to verify network functionality:

* Router neighbor verification
* End-to-end ping tests between routers
* Server connectivity tests
* PC to server communication
* Route verification using routing tables

Successful tests confirmed that all routers could learn routes dynamically and that end devices could communicate across the network.

---

## Project Screenshots

Screenshots include:

* Network topology diagram
* IPv6 addressing configuration
* OSPF neighbor verification
* Successful ping tests between routers
* PC to server connectivity

---

## Author

Kimberly Savai
BSc Telecommunications and Information Engineering
