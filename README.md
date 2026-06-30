# Cisco Packet Tracer – PC to PC Communication

A beginner-friendly Cisco Packet Tracer lab demonstrating how devices communicate within a Local Area Network (LAN). This project explains ARP, ICMP, MAC address learning, and Ethernet switching using Simulation Mode.

## 📌 Objective

Understand how a switch forwards packets and how PCs communicate in the same network.

## 🛠️ Lab Setup

- 1 × Cisco Catalyst 2960 Switch
- 3 × PCs
- Copper Straight-Through Cables

## 🌐 IP Addressing

| Device | IP Address | Subnet Mask |
|---------|------------|-------------|
| PC0 | 192.168.1.1 | 255.255.255.0 |
| PC1 | 192.168.1.2 | 255.255.255.0 |
| PC2 | 192.168.1.3 | 255.255.255.0 |

## 📖 Concepts Covered

- ARP (Address Resolution Protocol)
- ICMP (Ping)
- Broadcast vs Unicast
- MAC Address Learning
- Ethernet Switching
- Packet Flow Analysis

## 🔄 Packet Flow

1. 🟧 ARP Request (Broadcast)
2. 🟩 ARP Reply (Unicast)
3. 🩷 ICMP Echo Request
4. 🩷 ICMP Echo Reply

## 🧪 Verification

Ping from PC0 to PC1:

```bash
ping 192.168.1.2
```

View the MAC address table:

```bash
enable
show mac address-table
```

## 📂 Repository Contents

```
📁 Cisco-Packet-Tracer-PC-Communication
│── README.md
│── PC_to_PC_Communication.pkt
│── images/
│   ├── topology.png
│   ├── arp-request.png
│   ├── arp-reply.png
│   └── packet-flow.gif
```

## 🎯 Learning Outcomes

- Learned how ARP resolves IP addresses to MAC addresses.
- Understood ICMP Echo Request and Echo Reply.
- Observed how switches learn MAC addresses dynamically.
- Explored Broadcast and Unicast communication.
- Practiced network troubleshooting using Simulation Mode.

## 👨‍💻 Author

**Gunal G**

MCA Student | Linux | Networking | Cybersecurity Enthusiast

---

⭐ If you found this project useful, consider giving this repository a star!
