# Head Office & Branch Office Network – VLAN + SVI + OSPF Lab
This repository contains a Cisco Packet Tracer lab where a Head Office network with 3 VLANs is connected to a Branch Office network with 1 VLAN, using SVIs and OSPF routing to achieve full inter-site connectivity.

Network Overview
Head Office
VLAN 10 – IT
VLAN 20 – SALES
VLAN 30 – BANK

SVIs created on Layer 3 switch for inter-VLAN routing
OSPF enabled to advertise all VLAN networks

Branch Office
VLAN 20 – SALES

OSPF used to share the branch network with the Head Office

Technologies Used:
VLAN segmentation
SVI (Switched Virtual Interface) Configuration
Inter-VLAN routing
OSPF dynamic routing
Point-to-point WAN link simulation

 What This Lab Covers:

Designing a multi-site network
Creating VLANs and assigning switch ports
Configuring SVIs for gateway assignment
Establishing OSPF (process ID, network statements, router-ID)

Verifying routing tables and cross-VLAN communication

Testing reachability between Head Office & Branch Office
