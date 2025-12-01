# Head Office & Branch Office Network – VLAN + SVI + OSPF Lab
This repository contains a Cisco Packet Tracer lab where a Head Office network with 3 VLANs is connected to a Branch Office network with 1 VLAN, using SVIs and OSPF routing to achieve full inter-site connectivity.

📌 Network Overview:

Head Office
VLAN 10 – IT
VLAN 20 – SALES
VLAN 30 – BANK

SVIs created on Layer 3 switch for inter-VLAN routing
OSPF enabled to advertise all VLAN networks

Branch Office:

VLAN 20 – SALES

OSPF used to share the branch network with the Head Office

📡 Technologies Used:

VLAN segmentation
SVI (Switched Virtual Interface) Configuration
Inter-VLAN routing
OSPF dynamic routing
Point-to-point WAN link simulation

🧩 What This Lab Covers:

Designing a multi-site network
Creating VLANs and assigning switch ports
Configuring SVIs for gateway assignment
Establishing OSPF (process ID, network statements, router-ID)
Verifying routing tables and cross-VLAN communication
Testing reachability between Head Office & Branch Office

📊 Final Implementation Snapshot:

<img width="1538" height="683" alt="image" src="https://github.com/user-attachments/assets/6d1da984-7fa2-4aa7-b816-f33104641ac0" />

✅ Verification & Testing - Devices in different network communicate successfully.

<img width="1912" height="960" alt="image" src="https://github.com/user-attachments/assets/c3accf68-abee-4418-8c08-a8ed6e851a91" />

👨‍💻 Author Sai Charen

Skilled in Networking, Cisco Packet Tracer, and Enterprise IT Solutions.


