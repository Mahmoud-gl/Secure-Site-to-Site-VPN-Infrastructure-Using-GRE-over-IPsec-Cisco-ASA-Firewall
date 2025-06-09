# 🔐 Secure Site-to-Site VPN Infrastructure Using GRE over IPsec + Cisco ASA Firewall

## 📌 Project Overview

In today’s cybersecurity-driven world, financial institutions demand secure, redundant, and scalable infrastructure.  
This project delivers a **fully secured enterprise network**, integrating **GRE over IPsec tunnels**, **Cisco ASA Firewalls**, and **dynamic routing protocols** for a real-world scenario emulated in **EVE-NG**.

## 🧠 Use Case
This implementation targets a **mid-sized financial institution** connecting a **Head Office**, **Branch**, and **Data Center** with an **AWS Cloud Environment**, while complying with:

- 🔒 ISO/IEC 27001  
- 💳 PCI-DSS  
- 🛡️ NIST Cybersecurity Framework (CSF)  

---

## 🚀 Technologies & Features

### 🖧 LAN Infrastructure
- Hierarchical Network Design using **EVE-NG**
- VLAN Design for Departments + Native VLAN 999
- VLAN Trunking Protocol (VTP) across Distribution & Access layers
- HSRP for Layer 3 Gateway Redundancy
- EtherChannel (PAGP) on Core-Switches
- Inter-VLAN Routing (SVI)
- iBGP for Internal Routing

### 🏢 Data Center
- VLAN 99 for DC Segment
- Domain Controller & DNS Configuration
- NAS Storage and File Server via FileZilla

### 🌐 ISP Environment
- eBGP Routing for Multi-ISP Edge Routers

### 🔐 Security Infrastructure (Cisco ASA)
- Port Security, DHCP Snooping, Dynamic ARP Inspection
- ASA with:
  - NAT Policies  
  - ACLs (HTTP, TCP, UDP, ICMP)  
  - MPF (Modular Policy Framework)  
  - SSH & DHCP Services  
  - High Availability (Failover)  
  - AAA, NFP Hardening  
  - SSL VPN & IPsec Site-to-Site VPN with GRE  
  - Web Filtering + IDS/IPS Technologies  

---

## 🧪 Tools Used
- Cisco ASA
- Cisco IOS Routers & Switches
- EVE-NG Emulator
- Windows Server (Domain Controller, DNS)
- FileZilla Server


| Topology | ASA Configuration | VPN Tunnel |
|---------|-------------------|------------|
| ![topology](diagrams/topology.png) | ![asa](diagrams/asa-config.png) | ![vpn](diagrams/vpn-status.png) |

---

## 🙋‍♂️ Author

**Mahmoud Gamal**  
📧 Contact: [LinkedIn](https://www.linkedin.com/in/mahmoud-gamal/)  
🔗 GitHub: [github.com/Mahmoud-gl](https://github.com/Mahmoud-gl)  
🛠️ Network Infrastructure Engineer  

---

## 📣 Contributions & Feedback

Pull requests and suggestions are welcome!  
If you find this useful, feel free to ⭐ the repo and share it on LinkedIn.

---

## 📥 License

This project is licensed under the MIT License.


