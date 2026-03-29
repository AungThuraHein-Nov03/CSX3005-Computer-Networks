<div align="center">

# CSX3005
## Computer Networks

**Assumption University &middot; Academic Year 2025**

<br />

Based on
*Computer Networking: A Top-Down Approach, 8th Global Edition*
by **Jim Kurose** & **Keith Ross** (Pearson, 2022)

<br />

[![Textbook](https://img.shields.io/badge/Textbook-Kurose_%26_Ross_8th_Ed-blue)]()
[![Semester](https://img.shields.io/badge/Semester-2.2025-green)]()
[![Institution](https://img.shields.io/badge/Institution-Assumption_Univ.-purple)]()

</div>

---

## Overview

This repository contains the lecture slides for the CSX3005 Computer Networks course. The curriculum follows the top-down approach of the Kurose & Ross textbook, beginning with the application layer and working down through the network, transport, and link layers -- the same way network applications are built in practice.

> **Note:** The full textbook PDF is included in this repository. Individual chapter slides are provided below for quick reference.

---

## Course Structure

| # | Chapter | Format | Topics |
|:-:|---------|--------|--------|
| 1 | [Introduction](Chapter_1_v8.2_2_2025.pdf) | PDF | What is the Internet, protocol basics, network edge & core, performance, security, layering, history |
| 2 | [Application Layer](Chapter_2_v8.2_2_2025.pptx) | PPTX | HTTP, DNS, SMTP, IMAP, P2P, video streaming, CDNs, socket programming (TCP/UDP) |
| 4 | [Network Layer: Data Plane](Chapter_4_v8.2_2_2025.pptx) | PPTX | Router architecture, forwarding, IP protocol, IPv4 addressing, NAT, IPv6, SDN forwarding |
| 5 | [Network Layer: Control Plane](Chapter_5_v8.2_2_2025.pptx) | PPTX | Routing algorithms (link-state, distance-vector), OSPF, BGP, ICMP, SDN control, SNMP |
| 6 | [Link Layer and LANs](Chapter_6_v8.2_2_2025.pptx) | PPTX | Error detection/correction, multiple access protocols, ARP, Ethernet, switches, VLANs |
| 7 | [Wireless and Mobile Networks](Chapter_7_v8.2_2_2025.pptx) | PPTX | WiFi (802.11), cellular networks (4G/5G), spectrum, wireless vs. mobility |

---

## Chapter Details

### 1. Introduction

Foundational concepts that set the stage for the entire course. Introduces the Internet as a *network of networks* comprising billions of connected computing devices, packet switches (routers and switches), communication links (fiber, copper, radio, satellite), and protocols (HTTP, TCP, IP, WiFi, 4G/5G, Ethernet). Covers the distinction between the **network edge** (hosts, access networks, physical media) and the **network core** (packet switching vs. circuit switching), defines key performance metrics (delay, loss, throughput), and introduces the layered protocol architecture.

### 2. Application Layer

Explores how real-world network applications operate. Examines the **client-server** and **peer-to-peer** paradigms, then dives into the protocols that power everyday services:

- **Web** -- HTTP/1.1, HTTP/2, cookies, and web caching
- **Email** -- SMTP, IMAP
- **DNS** -- the Internet's directory service
- **Content Delivery** -- P2P file sharing, video streaming, CDNs
- **Hands-on** -- Socket programming with UDP and TCP

### 4. Network Layer: Data Plane

Focuses on the **forwarding** function -- how individual routers move packets from input to output. Covers router internals (input ports, switching fabric, output ports), buffer management and scheduling disciplines, the **IP protocol** (datagram format, IPv4 addressing and subnetting), **NAT**, **IPv6**, and the shift toward generalized forwarding in SDN architectures.

### 5. Network Layer: Control Plane

Focuses on the **routing** function -- how paths are computed across the network. Contrasts traditional per-router control with the centralized approach of **Software-Defined Networking (SDN)**. Covers routing algorithms (link-state and distance-vector), intra-domain routing (**OSPF**), inter-domain routing (**BGP**), **ICMP**, and network management with **SNMP**.

### 6. The Link Layer and LANs

Examines how data is transferred over individual links. Covers link-layer services (framing, link access, reliable delivery), **error detection and correction** techniques, **multiple access protocols** (ALOHA, CSMA/CD, CSMA/CA, TDMA, FDMA), **LAN addressing** and **ARP**, **Ethernet** standards, **switches**, and **VLANs**.

### 7. Wireless and Mobile Networks

Explores the unique characteristics and challenges of wireless communication. Covers wireless link properties, the **IEEE 802.11 (WiFi)** standard for wireless LANs, **cellular network** architectures including **4G LTE** and **5G**, and makes an important distinction between *being wireless* (connectivity) and *being mobile* (movement across networks).

---

## Learning Outcomes

Upon completion of this course, students will be able to:

1. **Describe the Internet's architecture**
   Explain the Internet as a layered network of networks; identify key components (hosts, routers, links, protocols) and trace a packet's journey from source to destination.

2. **Explain protocol layering and service models**
   Articulate why protocols are organized into layers; describe the responsibilities of each layer (application, transport, network, link, physical) and the service models they provide.

3. **Analyze network application protocols**
   Compare client-server and peer-to-peer models; explain how HTTP, DNS, SMTP, and IMAP work; evaluate the role of CDNs in modern content delivery.

4. **Implement socket programming**
   Write basic network applications using UDP and TCP sockets; understand the trade-offs between the two in terms of reliability, ordering, and overhead.

5. **Explain router forwarding and the data plane**
   Describe how routers forward packets using longest-prefix matching; explain router architecture and understand IP addressing, subnetting, NAT, and IPv6.

6. **Analyze routing algorithms and the control plane**
   Compare link-state and distance-vector routing; explain OSPF within autonomous systems and BGP between ISPs; contrast traditional control with SDN.

7. **Describe link-layer technologies and LANs**
   Explain error detection and correction mechanisms; compare multiple access protocols; describe Ethernet and switching operation, MAC addressing, and ARP.

8. **Evaluate wireless and mobile network technologies**
   Explain challenges unique to wireless communication; describe WiFi (802.11) and cellular architectures (4G/5G); understand how mobility is managed separately from wireless connectivity.

9. **Apply performance analysis**
   Calculate and interpret network performance metrics including delay (queuing, processing, transmission, propagation), loss, and throughput.

10. **Recognize security considerations**
    Identify common network security threats and understand basic security mechanisms across layers of the network stack.

---

<div align="center">
<i>Slides are adapted from the official Kurose & Ross 8th Edition lecture materials.</i>
</div>
