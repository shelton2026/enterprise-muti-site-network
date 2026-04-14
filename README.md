# Enterprise Multi-Site Network 2 (OSPF + VPN + Firewall)

## 📌 Overview
Designed and implemented a secure enterprise network connecting a headquarters (HQ) and multiple branch offices. This project simulates a real-world company network with routing, switching, and security technologies.

---

## 🏗️ Architecture
- 3-tier architecture (Core, Distribution, Access)
- Centralized services at HQ
- Multiple branch offices connected over WAN
- Firewall placed at the edge for security

---

## 🌐 Technologies Used
- VLANs & Inter-VLAN Routing
- OSPF (Dynamic Routing)
- GRE Tunnel + IPsec VPN
- Firewall (ASA)
- NAT (Dynamic & Static) 
- DHCP with relay (ip helper-address)

---

## 🔐 Security Implementation
- Firewall ACLs allowing only HTTP/HTTPS traffic from the Internet
- Internal ACLs restricting access to servers
- VLAN segmentation to isolate users and servers
- NAT to hide internal private IP addresses

---

## 🌍 WAN Connectivity
- Site-to-site VPN using GRE over IPsec
- OSPF running over tunnel interfaces
- Dynamic route exchange between HQ and branches

---

## 🧪 Verification & Testing
- OSPF neighbors successfully established between sites
- End-to-end connectivity verified using ping
- NAT translations validated on firewall
- Web server accessible from internal and external networks
- Simulated attacks (ping, telnet) successfully blocked by ACLs

---

## 📸 Screenshots
- Network topology
- OSPF neighbor status
- NAT operation
- VPN tunnel status
- Web server access
- DNS-server
---

## 🚀 Outcome
Built a scalable and secure enterprise network that demonstrates real-world networking concepts including routing, switching, WAN connectivity, and network security.

---

## 💡 Key Skills Demonstrated
- Network design and architecture
- Troubleshooting and verification
- Security implementation (ACLs, Firewall, NAT)
- WAN technologies (VPN, GRE, OSPF)enterprise-muti-site-network

- ## configs
- branch1 router
- branch2 router
- edge-router
- hq-core-l3 switch
- firewall
