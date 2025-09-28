# 🏢 Enterprise Network Infrastructure – Mega Lab (SVI)

---

## 📘 Project Overview

This is a comprehensive **network simulation lab** inspired by the **CCNA 200-301 curriculum**. It replicates a real-world **enterprise network** using:

- VLAN segmentation  
- Inter-VLAN routing via SVI (Switch Virtual Interfaces)  
- Layer 2 redundancy (STP, EtherChannel)  
- Centralized IP addressing with DHCP  
- Multi-Area OSPF Routing  
- DHCP Relay Agent

> 🛠️ Built using **Cisco Packet Tracer**, this lab emphasizes practical implementation of essential Layer 2 & Layer 3 technologies.

---

## 🎯 Learning Objectives

- ✅ Design a scalable and segmented enterprise network  
- ✅ Implement core CCNA technologies (VLANs, SVI, DHCP, OSPF)  
- ✅ Understand how dynamic routing protocols operate  
- ✅ Improve hands-on troubleshooting and configuration skills

---

## 🧩 Lab Components

- 🖧 Multiple Layer 2 and Layer 3 Cisco Switches  
- 📡 Cisco Routers  
- 🖥️ End Devices (PCs/Clients)  
- 🌐 Simulated Internet connection  
- 🎯 DHCP Server  
- 🧱 VLAN-configured segments  

---

## 🧪 Technologies Used

| Technology            | Purpose                                      |
|----------------------|----------------------------------------------|
| **VLANs**            | Logical segmentation of traffic              |
| **SVI**              | Inter-VLAN routing via Layer 3 switch        |
| **STP**              | Prevent switching loops, define root bridge  |
| **EtherChannel**     | Link aggregation for bandwidth/redundancy    |
| **DHCP**             | IP address distribution per VLAN             |
| **DHCP Relay Agent** | Forward DHCP requests across router hops     |
| **OSPF (Multi-Area)**| Dynamic routing between areas & segments     |

---

## ⚙️ Implementation Steps

1. Configure VLANs on all access and distribution switches  
2. Enable SVIs for inter-VLAN routing on multilayer switches  
3. Configure **STP** and define the Root Bridge  
4. Aggregate switch links using **EtherChannel** (LACP or PAgP)  
5. Set up **DHCP pools** for each VLAN  
6. Enable **DHCP Relay** on routers for remote VLANs  
7. Configure **OSPF Multi-Area** routing  
8. Verify connectivity using `ping`, `traceroute`, and `show` commands  

---

## ✅ Outcomes

- 🎯 Enterprise network simulation completed  
- 📡 VLANs function with correct segmentation and IP assignment  
- 🔄 Inter-VLAN routing (via SVI) is fully functional  
- 🔁 Redundancy achieved through STP and EtherChannel  
- 🌍 OSPF routing works across multiple areas  
- ✅ End-to-end connectivity verified

---

## 📂 Project Files

| File                  | Description                               |
|-----------------------|-------------------------------------------|
| [`EnterpriseNetwork.pkt`](./EnterpriseNetwork.pkt) | Main Cisco Packet Tracer file           |
| [`topology.png`](./topology.png)                 | Network topology diagram               |
| [`subnet-plan.png`](./subnet-plan.png)           | Subnetting and IP planning chart       |
| [`Documentation.pdf`](./Documentation.pdf)       | Full technical report                  |
| [`README.md`](./README.md)                       | This documentation file                |

---

## 📸 Preview

![Network Topology](https://postimg.cc/qt6DNBtz)

---

 

<p align="right">
  <img src="https://i.postimg.cc/yxy6x7F6/image.png" width="32" valign="middle">
  <a href="mailto:zezorehan938@gmail.com" style="font-weight:bold; font-size:20px; text-decoration:underline; color:#2e89ff;">
    𝓩𝓲𝓪𝓭𝓻𝓮𝓱𝓪𝓪𝓷
  </a>
</p>
