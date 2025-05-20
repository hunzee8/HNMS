# Hotel Network Management System : A Computer Networks project

This project demonstrates the design and configuration of a scalable, secure, and efficient network infrastructure tailored to the needs of a hotel environment.

## 📌 Project Objectives

- Design a structured network architecture for a hotel.
- Implement static and dynamic IP allocation.
- Enable secure departmental communication via VLANs.
- Establish dynamic routing using EIGRP for fault tolerance and scalability.
- Provide internet access to both hotel guests and internal departments.

---

## 🧠 Concepts Used

### 1. Static IP Assignment
- Reserved for servers, printers, and critical departmental devices.
- Ensures consistent connectivity and simplified troubleshooting.

### 2. Dynamic IP Assignment (DHCP)
- Configured on routers to assign IPs to guest and employee devices.
- Reduces administrative load and supports large device turnover.

### 3. VLAN Segmentation & Inter-VLAN Communication
- VLAN 10: Marketing
- VLAN 20: IT Department
- VLAN 30: Guests
- Inter-VLAN routing enabled via a Layer 3 switch.

### 4. Dynamic Routing with EIGRP
- Efficient routing between floors and departments.
- Backup paths for fault tolerance and minimal downtime.

---

## ⚙️ Implementation Details

- **Routers**: Connected floor-wise and handle DHCP, static IP allocation, and routing.
- **Switches**: Manage VLANs and departmental traffic.
- **End Devices**: Include staff workstations, guest devices, servers, and printers.

---

## ✅ Results & Outcomes

- ✔️ Seamless IP allocation and management.
- ✔️ Improved network security via VLANs.
- ✔️ High availability using dynamic routing.
- ✔️ Scalable and easily extendable architecture.
- ✔️ Enhanced guest experience with a separate VLAN.
- ✔️ Simplified maintenance and diagnostics.

---

