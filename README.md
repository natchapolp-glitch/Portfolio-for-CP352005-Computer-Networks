<div align="center">

# 🎓 Academic Portfolio

### นายณัชพล เพ็งพล (Natchaphon Phengphon)

**รหัสนักศึกษา:** `673380267-4`




</div>

---

## 📑 Table of Contents


- [📂 Portfolio Structure](- 📂 **[Portfolio Structure](https://github.com/natchapolp-glitch/Portfolio-for-CP352005-Computer-Networks/tree/main#-portfolio-structure)** )
- [🧪 Group Work — Lab Reports](- 👥 **[Group Work](https://github.com/natchapolp-glitch/Portfolio-for-CP352005-Computer-Networks/tree/main/GroupWork)** )
- [📝 Personal Work](- 📁 **[Personal Work](https://github.com/natchapolp-glitch/Portfolio-for-CP352005-Computer-Networks/tree/main/Personal_Work)** )
- [📜 Certification](- 📜 **[CCNA Introduction to Networks Certificate](https://github.com/natchapolp-glitch/Portfolio-for-CP352005-Computer-Networks/blob/main/Certificate/CCNA-_Introduction_to_Networks_certificate_natchapol-p-kkumail-com_264f841f-ea91-42f2-abb5-d3d8b926cb4b.pdf)** )
- [🔗 Links](#-links)

---

## 👤 About Me

สวัสดีครับ ผม **ณัชพล เพ็งพล** รหัสนักศึกษา **673380267-4** มีความสนใจด้าน **Computer Networking** และ **Infrastructure** โดย Portfolio นี้เป็นการรวบรวมผลงานจากการเรียนรู้ทั้งงานกลุ่มและงานเดี่ยว ครอบคลุมตั้งแต่พื้นฐาน Network ไปจนถึงการออกแบบระบบเครือข่ายขั้นสูง

---

## 🛠️ Technical Skills

<div align="center">

| Category | Skills |
|:---|:---|
| **Network Fundamentals** | IP Addressing, Subnetting, ARP, MAC Address Table |
| **Routing & Switching** | Static Routing, Inter-VLAN Routing, Router-on-a-Stick, NAT |
| **VLAN & Trunking** | VLAN Configuration, 802.1Q Trunking, VLAN Security |
| **Tools & Software** | Cisco Packet Tracer, Wireshark, VS Code |
| **Protocols** | TCP/IP, ICMP, ARP, HTTP, MIME, JSON |
| **Infrastructure as Code** | Docker (Mockup Infra), Stateless/Stateful Services |
| **Troubleshooting** | Network Diagnostics, Ping, Traceroute, ARP Inspection |

</div>

---

## 📂 Portfolio Structure

```
Port/
├── 📁 Certificate/           # ใบรับรองและประกาศนียบัตร
│   ├── CCNA_Introduction_to_Networks.pdf
│   └── Screenshot.png
│
├── 📁 GroupWork/              # ผลงานกลุ่ม (Lab Reports)
│   ├── LAB 1.md               # Basic Network Connectivity & ARP
│   ├── Lab 2.md               # VLAN Design — Router-on-a-Stick
│   ├── Lab3.md                # MIME File Transfer & Wireshark
│   ├── Lab4.md                # Simulated Internet & NAT
│   ├── New Network.docx       # Network Design Document
│   └── Github_Final_Project   # → Final Project Repository
│
├── 📁 Personal_Work/          # ผลงานเดี่ยว
│   ├── Assignment 2.pdf
│   ├── ass3.pkt               # Packet Tracer Simulation
│   ├── ass4.pdf
│   ├── lab 5.pdf
│   └── personal essay.pdf
│
└── 📄 README.md               # ← You are here
```

---

## 🧪 Group Work — Lab Reports

### 🔬 Lab 1: Basic Network Connectivity & ARP Analysis

> **หัวข้อ:** Complete Lab-Focused Teaching Package
>
> **บทบาท:** รับผิดชอบ **Part 4**

| รายละเอียด | ข้อมูล |
|:---|:---|
| **Network** | `192.168.1.0/24` |
| **Devices** | Router (R1), Switch (S1), PC1, PC2 |
| **เนื้อหาหลัก** | Topology Design, IP Addressing, Connectivity Verification, ARP Table Analysis, Troubleshooting |

**สิ่งที่ได้เรียนรู้:**
- การออกแบบ Topology และกำหนด Addressing Table
- การตรวจสอบ Connectivity ด้วย Ping ระหว่างอุปกรณ์
- การวิเคราะห์ ARP Table และ MAC Address
- การแก้ไขปัญหาเครือข่าย (Troubleshooting)

---

### 🔬 Lab 2: Secure & Scalable VLAN Design (Router-on-a-Stick)

> **หัวข้อ:** Inter-VLAN Routing with 802.1Q Trunk
>
> **บทบาท:** รับผิดชอบ **Part 5**

| รายละเอียด | ข้อมูล |
|:---|:---|
| **Network** | `192.168.10.0/24` (Subnetted /26) |
| **VLANs** | VLAN 10 (`192.168.10.0/26`), VLAN 20 (`192.168.10.64/26`), VLAN 99 (`192.168.10.128/26`) |
| **Devices** | Router (R1), Switch (S1), PC-A, PC-B, PC-C |
| **เนื้อหาหลัก** | VLAN Configuration, 802.1Q Trunking, Sub-interfaces, Inter-VLAN Routing |

**สิ่งที่ได้เรียนรู้:**
- การออกแบบ Subnet สำหรับ VLAN หลายตัว
- การ Config Router-on-a-Stick สำหรับ Inter-VLAN Routing
- การจัดการ VLAN Trunking และ Security
- การตรวจสอบการเชื่อมต่อข้าม VLAN

---

### 🔬 Lab 3: MIME File Transfer & Wireshark Analysis

> **หัวข้อ:** MIME File Transfer over Router-on-a-Stick with Wireshark Analysis

| รายละเอียด | ข้อมูล |
|:---|:---|
| **Scenario** | Client ใน VLAN หนึ่งส่งไฟล์ไปยัง Server ใน VLAN อื่นผ่าน Custom MIME Protocol |
| **Tools** | Python 3, Wireshark, Cisco Packet Tracer |
| **เนื้อหาหลัก** | Socket Programming, MIME Protocol, Packet Capture, OSI Layer Analysis |

**สิ่งที่ได้เรียนรู้:**
- การ Deploy MIME Socket Server/Client ข้าม VLAN
- การ Capture และวิเคราะห์ Traffic ด้วย Wireshark
- การระบุ ARP, VLAN Tags, TCP Handshake ใน Packet
- การ Decode JSON Header ใน Application Layer
- การ Troubleshoot ปัญหาทั้ง Network และ Application

---

### 🔬 Lab 4: Simulated Internet & NAT with Stateful/Stateless Services

> **หัวข้อ:** Simulated Internet (10.10.0.0/16) & Private LANs with Stateful vs Stateless Services

| รายละเอียด | ข้อมูล |
|:---|:---|
| **Public Network** | `10.10.12.0/30` (Simulated Internet) |
| **Private LANs** | Lab A & Lab B — แต่ละ Lab มี Local Subnet |
| **เนื้อหาหลัก** | Static Routing, NAT, Docker Deployment, Stateless vs Stateful APIs |

**สิ่งที่ได้เรียนรู้:**
- การออกแบบเครือข่ายที่มี Public/Private Network แยกกัน
- การ Config Static Route และ NAT บน Cisco Router
- การ Deploy Stateless/Stateful Services ด้วย Infrastructure as Code
- การเปรียบเทียบ Session Behavior ระหว่าง Local กับ Remote

---

## 📝 Personal Work

| ไฟล์ | รายละเอียด |
|:---|:---|
| **Assignment 2** | งานมอบหมายรายบุคคล |
| **Assignment 3** | Cisco Packet Tracer Simulation (`.pkt`) |
| **Assignment 4** | งานมอบหมายรายบุคคล |
| **Lab 5** | Lab Report เดี่ยว |
| **Personal Essay** | เรียงความส่วนตัว |

---

## 📜 Certification

<div align="center">

### 🏅 Cisco Certified Network Associate (CCNA)

**Introduction to Networks**

[![CCNA Badge](https://img.shields.io/badge/Cisco-CCNA_ITN-049FD9?style=for-the-badge&logo=cisco&logoColor=white)](#)

✅ **Status:** Completed

> ใบรับรองอยู่ในโฟลเดอร์- 📜 **[CCNA Introduction to Networks Certificate](https://github.com/natchapolp-glitch/Portfolio-for-CP352005-Computer-Networks/blob/main/Certificate/CCNA-_Introduction_to_Networks_certificate_natchapol-p-kkumail-com_264f841f-ea91-42f2-abb5-d3d8b926cb4b.pdf)** – Cisco Networking Academy

</div>

---

## 🔗 Links

| แหล่ง | ลิงก์ |
|:---|:---|
| 🌐 **Final Project (Group 14)** | [github.com/natchapolp-glitch/Group-14](https://github.com/natchapolp-glitch/Group-14) |
| 👤 **GitHub Profile** | [github.com/natchapolp-glitch](https://github.com/natchapolp-glitch) |

---

<div align="center">

### 🙏 ขอบคุณที่เข้ามาชม Portfolio ครับ

*Made with ❤️ by Natchaphon Phengphon*

**673380267-4 | Khon Kaen University**

</div>
