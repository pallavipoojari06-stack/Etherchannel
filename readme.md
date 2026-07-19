# EtherChannel Configuration in Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates how to configure **EtherChannel** in Cisco Packet Tracer using all three methods:

- **Static EtherChannel (Mode ON)**
- **PAgP (Port Aggregation Protocol) – Cisco Proprietary**
- **LACP (Link Aggregation Control Protocol) – IEEE 802.3ad Standard**

EtherChannel combines multiple physical links into a single logical connection, increasing bandwidth and providing redundancy. If one cable fails, the remaining links continue forwarding traffic.

---

## 🎯 Objectives

- Understand the concept of EtherChannel.
- Configure Static EtherChannel.
- Configure Dynamic EtherChannel using PAgP.
- Configure Dynamic EtherChannel using LACP.
- Verify EtherChannel operation.
- Test redundancy and load balancing.

---

## 🛠️ Software Used

- Cisco Packet Tracer
- Cisco IOS CLI

---



# 📚 EtherChannel Modes Summary

| Protocol | Mode | Description |
|----------|------|-------------|
| Static | on | No negotiation |
| PAgP | desirable | Actively negotiates |
| PAgP | auto | Passively waits |
| LACP | active | Actively negotiates |
| LACP | passive | Passively waits |

---

# 📖 Key Differences

| Feature | Static | PAgP | LACP |
|----------|--------|------|------|
| Negotiation | No | Yes | Yes |
| Standard | No | Cisco Proprietary | IEEE 802.3ad |
| Compatibility | Cisco | Cisco Only | Multi-vendor |
| Recommended | Small Labs | Cisco Networks | Enterprise Networks |

---

# 🚀 Learning Outcomes

After completing this project, you will be able to:

- Understand EtherChannel concepts.
- Configure Static EtherChannel.
- Configure PAgP EtherChannel.
- Configure LACP EtherChannel.
- Verify EtherChannel status.
- Test redundancy and fault tolerance.
- Apply EtherChannel in Cisco Packet Tracer labs.

---

## 👩‍💻 Author

**Pallavi Poojari**

Cybersecurity & Networking Enthusiast

- Cisco Packet Tracer
- CCNA Learning
- VLANs
- Switching
- Routing
- EtherChannel
