# Digital Egypt Pioneers Initiative (DEPI)

## Tracker Infrastructure and Security

### Google IT Technical Support Specialist Track 2024

---

## Project Overview

**Title:** Network Setup and Troubleshooting  
**Submitted By:** AbdulRhman AbdulGhaffar, Mustafa Abdullah, and Ramzey Elsayed  
**Under the Supervision of:** DR. Mustafa Salah

**Document Submitted in Partial Fulfillment of the Requirements for Network Setup and Troubleshooting in Digital Egypt Pioneers Initiative Track (Google IT Technical Support Specialist).**

---

## Introduction

This project focuses on the design, implementation, and troubleshooting of a secure and scalable network infrastructure using Cisco devices and Windows Server technologies. It aims to provide an efficient network setup and seamless operations to ensure optimal performance and reliability.

---

## Team Roles and Responsibilities

### AbdulRhman AbdulGhaffar Ewais
- **Role:** Windows Server Configuration Specialist
- **Responsibilities:**
  - Configuring network settings
  - Designing and implementing network infrastructure
  - Ensuring security settings and connection integrity
  - Hands-on experience with communication protocols and network device operations

### Mustafa Abdullah Mohammed
- **Role:** Network Design Specialist
- **Responsibilities:**
  - Designing network topologies
  - Determining hardware and software requirements
  - Creating scalable network architectures
  - Ensuring performance and security standards

### Ramzey Elsayed Mohammed
- **Role:** Troubleshooting Specialist
- **Responsibilities:**
  - Identifying and resolving network issues
  - Conducting connectivity tests and analyzing traffic
  - Performing routine maintenance to prevent disruptions
  - Ensuring stability and reliability of operations

---

## Supervisor's Profile

**DR. Mustafa Salah**
- IT Support professional dedicated to providing technical support to end-users
- Expertise in troubleshooting hardware and software issues, configuring systems, and delivering excellent customer experiences
- Passionate about solving user problems and achieving successful resolutions

---

## Project Documentation

### Table of Contents
1. [Introduction](#introduction)
2. [Project Objectives](#project-objectives)
3. [System Architecture](#system-architecture)
4. [Implementation Details](#implementation-details)
5. [Troubleshooting Process](#troubleshooting-process)
6. [Outcomes](#outcomes)
7. [Future Enhancements](#future-enhancements)
8. [References](#references)

---

## Project Objectives
- To design a robust network infrastructure using Cisco devices
- To configure and optimize Windows Server environments
- To implement effective troubleshooting techniques

---

## System Architecture

**Include Network Topology Diagram:**  
*Add a network topology image here (e.g., using Cisco Packet Tracer)*

# Network Design & Configuration

## 📌 Overview
This project demonstrates a structured network topology designed using **Cisco Packet Tracer**. The network includes various interconnected devices, each assigned a specific role to ensure seamless communication and efficient management.

### 🖥️ Network Components
- **Router (1841 R1):** Acts as the central hub for managing traffic.
- **Switch (Cisco 2960):** Distributes connectivity to different segments.
- **Access Points (Cisco 3702i):** Provide wireless connectivity to different departments.
- **Wireless LAN Controller (WLC-3504):** Centralized management of wireless devices.
- **Servers:** DHCP, DNS, and WEB servers handling key network services.
- **End-user Devices:** PCs and laptops connected via wired and wireless networks.

🔗 **Network Diagram:** [View Packet Tracer File](https://drive.google.com/file/d/1B_DEPuYSv7FYABG7J9TB13ulQaFx86Ij/view?usp=drive_link)

---

## 🏗️ Network Components & IP Configuration
| **Component** | **Device Name** | **IP Address** | **Function** |
|--------------|--------------|----------------|--------------|
| **Router** | 1841 R1 | 192.188.1.6 | Central traffic management |
| **DHCP Server** | Server-PT | 192.188.1.1 | Assigns dynamic IPs |
| **DNS Server** | Server-PT | 192.188.1.3 | Resolves domain names |
| **WEB Server** | Server-PT | 192.188.1.4 | Hosts web applications |
| **WLC** | WLC-3504 | 192.188.1.5 | Manages wireless networks |
| **PC (Management)** | PC-PT | 192.188.1.7 | Connected via VLAN |
| **Wireless APs** | Various | Dynamic | Provides wireless access |

🔗 **Full Configuration File:** [View Configuration](#)

---

## 🌐 Network Functionalities & Services
### 1️⃣ **DHCP Service**
- **Server IP:** `192.188.1.1`
- **IP Pool:** `192.188.1.10 - 192.188.1.50`
- **Default Gateway:** `192.188.1.6`

### 2️⃣ **DNS Service**
- **Server IP:** `192.188.1.3`
- **Domain:** `company.local`
- **Example Mapping:** `www.company.local → 192.188.1.4`

### 3️⃣ **WEB Server**
- **Server IP:** `192.188.1.4`
- **Services:** Internal web applications

🔗 **Server Configuration File:** [View Setup](#)

---

## 🔒 VLAN Configuration & Security
### 🔹 VLAN Segmentation
| **VLAN** | **Department** | **IP Range** |
|---------|--------------|-------------|
| VLAN 10 | IT Department | 192.188.1.50 - 192.188.1.60 |
| VLAN 20 | Management | 192.188.1.60 - 192.188.1.70 |
| VLAN 30 | Marketing | 192.188.1.70 - 192.188.1.80 |

✅ **Security Measures:**
- WPA3 enabled for wireless security.
- ACLs to restrict unauthorized access.

🔗 **VLAN Configuration Script:** [View VLAN Setup](#)

---

## 🛠️ Troubleshooting & Recommendations
### 🔍 **Common Issues & Solutions**
#### 🔹 **Connectivity Issues**
- Run `ping <destination IP>` to verify device reachability.
- Check DHCP assignments using `ipconfig /all`.

#### 🔹 **DNS Resolution Issues**
- Use `nslookup <domain-name>` to test name resolution.
- Ensure the correct DNS server is configured.

#### 🔹 **Wireless Connectivity Problems**
- Verify AP configurations via WLC.
- Check for interference or overlapping channels.

🔗 **Troubleshooting Guide:** [View Full Guide](#)

---

## 🚀 Conclusion & Future Enhancements
The network is well-structured for scalability and efficiency. Future improvements include:
✅ Adding redundancy with backup routers and switches.
✅ Upgrading to WPA3 for enhanced wireless security.
✅ Implementing SNMP for real-time network monitoring.

---
📌 **Repository Link:** [GitHub Repo](#)

🔗 **Packet Tracer File:** [Download Here](#)



---

## Implementation Details

### Tools and Technologies
- **Networking Devices:** Cisco Routers and Switches
- **Operating System:** Windows Server 2019
- **Simulation Software:** Cisco Packet Tracer

### Steps Taken
1. Designing the network topology
2. Configuring network devices
3. Setting up Windows Server for domain management
4. Implementing security policies
5. Testing and troubleshooting

---

## Troubleshooting Process

- **Challenges Identified:** Connectivity issues, misconfigurations, and hardware failures
- **Solutions Implemented:**
  - Analyzing logs and traffic data
  - Testing configurations
  - Replacing faulty hardware

---

## Outcomes
- Successfully designed and implemented a secure network
- Resolved critical issues and ensured optimal performance
- Enhanced practical understanding of network setup and troubleshooting

---

## Future Enhancements
- Integrating advanced monitoring tools
- Expanding network scalability
- Enhancing fault tolerance

---

## Project Files

| File Name                  | Description                          |
|----------------------------|--------------------------------------|
| `Documentation.pdf`       | Detailed project documentation       |
| `Proposal.pdf`            | Initial project proposal             |
| `Presentation.pptx`       | Final presentation slides            |
| `Network_Topology.pkt`    | Cisco Packet Tracer file             |
| `Windows_Server_Config`   | Configuration files for Windows Server |

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/aboodi200/DEPI-Network-Project.git
   ```

2. Access the project files and review the documentation.

3. Open the Packet Tracer file (`Network_Topology.pkt`) to visualize the network design.

4. Use the `Windows_Server_Config` files to replicate the server setup.

---

## References
- Cisco Networking Academy Materials
- Microsoft Windows Server Documentation
- Digital Egypt Pioneers Initiative Resources

---

## Acknowledgments

We extend our gratitude to:
- **DR. Mustafa Salah** for his invaluable guidance and support.
- The Ministry of Communications for offering this opportunity through the DEPI scholarship.

---

**[Download Full Documentation Here](#)**

**[Watch Presentation Video Here](#)**






