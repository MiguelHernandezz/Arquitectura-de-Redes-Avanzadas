<div align="center">

# 🌐 Arquitectura de Redes II · UAH

**Computer Networks II (Arquitectura de Redes II) · B.S. Computer Engineering · Universidad de Alcalá · 2025–2026**

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-161B22?style=flat-square)
![Team](https://img.shields.io/badge/team-2_people-00C853?style=flat-square)

</div>

Hands-on networking labs, from capturing real traffic in the UAH lab with **Wireshark** to building and debugging switched and wireless networks in **Cisco Packet Tracer**. These protocols are the ground floor of network security: what an attacker spoofs (ARP, DHCP), what a firewall filters (ICMP) and how VLANs segment a network.

> Done in a **team of 2**; my teammate's name has been removed from the reports for privacy. Practices 1 and 2 are not included yet.

---

## 📁 Contents

| Folder | Practice | Tool | Report |
|---|---|---|---|
| [`PL3-wireshark-icmp-dhcp`](PL3-wireshark-icmp-dhcp) | ICMP and DHCP in IPv4 | Wireshark | [Memoria_PL3.pdf](PL3-wireshark-icmp-dhcp/Memoria_PL3.pdf) |
| [`PL4-ethernet-arp`](PL4-ethernet-arp) | Ethernet MAC addressing and ARP | Wireshark | [Memoria_PL4.pdf](PL4-ethernet-arp/Memoria_PL4.pdf) |
| [`PL5-vlan-packet-tracer`](PL5-vlan-packet-tracer) | VLAN configuration and testing | Packet Tracer | [Memoria_PL5.pdf](PL5-vlan-packet-tracer/Memoria_PL5.pdf) |
| [`PL6-wifi-packet-tracer`](PL6-wifi-packet-tracer) | Wi-Fi network configuration and testing | Packet Tracer | [Memoria_PL6.pdf](PL6-wifi-packet-tracer/Memoria_PL6.pdf) |

---

## What each lab covers

**PL3 · ICMP and DHCP (Wireshark)**
- `ping` and `traceroute`/`tracert` captures: ICMP Echo Request/Reply and how **TTL** expiry reveals each hop.
- The full **DHCP** exchange (Discover → Offer → Request → ACK) triggered with `ipconfig /release` and `ipconfig /renew` on the lab PCs, and the lease parameters.

**PL4 · Ethernet and ARP (Wireshark)**
- Ethernet frame structure and **MAC addressing** (unicast vs broadcast).
- **ARP** request/reply on the wire, the ARP cache (`arp -a`) and how it fills when hosts talk to each other. This is the mechanism behind ARP spoofing.

**PL5 · VLANs (Packet Tracer)**
- Splitting one switched network into **VLANs**, access ports, and **802.1Q trunk** links between switches.
- Checking with `ping` and the MAC tables that broadcast and unicast traffic stay inside each VLAN.

**PL6 · Wi-Fi (Packet Tracer)**
- Setting up an **access point** and its **SSID**, with DHCP for the wireless clients.
- **Infrastructure mode** in simulation: following unicast and broadcast frames as every one goes through the AP, and checking end-to-end connectivity between wireless and wired hosts.

---

<!-- syllabus:start -->
## 📘 Syllabus · official UAH teaching guide

> **Redes de Computadores (780017)** · 6 ECTS · 2nd year · 2nd semester · contents from the 2025-26 teaching guide · [official subject page](https://www.uah.es/es/estudios/estudios-oficiales/grados/asignatura/Redes-de-Computadores-780017/)

| Unit | Hours | Topics |
|---|---|---|
| Network layer | 20 h | Virtual-circuit and datagram networks · IP and ICMP · Routing algorithms, OSPF and BGP · Addressing, DHCP and NAT |
| Link layer | 16 h | Link control and ARP · Medium access control, Ethernet and switches · VLANs and PPP · Wireless (Wi-Fi, Bluetooth) and mobile networks |
| Network security and management | 12 h | Network security and cryptography · Network management and administration |
| Integration exercises | 8 h | – |
<!-- syllabus:end -->

---

<div align="center">

Miguel Hernández López · [GitHub](https://github.com/MiguelHernandezz) · [LinkedIn](https://www.linkedin.com/in/miguel-hernandez-lopez/)

</div>
