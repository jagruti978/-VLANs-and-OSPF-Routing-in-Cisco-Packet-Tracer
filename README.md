# VLANs-and-OSPF-Routing-in-Cisco-Packet-Tracer
Designing and Implementing VLANs and OSPF Routing in Cisco Packet Tracer--[Computer Networks]

## Project Overview

This project involves designing and implementing a company network using VLANs, OSPF routing, and HSRP redundancy in Cisco Packet Tracer.
The goal is to create a structured, secure, and scalable network that supports inter-departmental communication and ensures high availability.

## Network Features

VLAN Segmentation: Divided the network into VLANs for Sales, Finance, IT, and Admin departments.

Dynamic Routing: Configured OSPF for efficient route management and inter-VLAN communication.

Redundancy: Used HSRP to ensure router failover and network reliability.

Realistic Simulation: Included routers, multilayer switches, access switches, PCs, and servers to replicate a real-world setup.

| Department | VLAN ID | IP Range       | Devices           |
| ---------- | ------- | -------------- | ----------------- |
| Sales      | 10      | 192.168.1.0/24 | PC1, PC5, PC8     |
| Finance    | 20      | 192.168.2.0/24 | PC2, PC6          |
| IT         | 30      | 192.168.3.0/24 | Server1, PC3      |
| Admin      | 40      | 192.168.4.0/24 | Server2, PC4, PC7 |

## Configuration Steps

Create VLANs and assign ports.

Configure Trunk Links between switches.

Assign IP addresses to VLAN interfaces.

Enable Inter-VLAN Routing on multilayer switches.

Set up HSRP for router redundancy.

Configure OSPF on routers for dynamic routing.

Test connectivity using ping across VLANs and routers.

## Key Learning Outcomes

VLAN configuration and segmentation

Trunking and inter-VLAN routing

OSPF dynamic routing setup

HSRP redundancy and failover testing

Network design and troubleshooting in Cisco Packet Tracer

## Result

The final network achieved:

Smooth inter-VLAN communication

Redundancy and high availability via HSRP

Efficient dynamic routing through OSPF

Secure and well-structured departmental segmentation

## Output
<img width="996" height="379" alt="image" src="https://github.com/user-attachments/assets/6be5fd23-a8f3-4895-8a76-3be359829898" />
