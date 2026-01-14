**Enterprise Data Center Design & Wireless Service Integration.**

**Project Overview** 
As a Network Engineer Trainee, I designed and simulated this scalable data center environment using Cisco Packet Tracer. Driven by a passion for networking, this project serves as a bridge between theoretical knowledge and real-world implementation. The goal was to build a robust system hosting multiple servers that provide seamless internet and web access to users via both wired and wireless technologies.2.

**Design Motivation**
  **Redundancy:** To demonstrate the ability to design complex, redundant network topologies that prevent single points of failure.
 **Security:** To practice implementing enterprise-grade security through DMZ and Access Control Lists (ACLs).
  **Real-World Simulation:** To replicate an end-to-end ISP-to-user workflow, ensuring high availability of data and web services.

**Network Infrastructure & Hardware**
The topology is segmented into functional zones for maximum efficiency:
 **Core & Distribution Layer:** Features a 3560-24PS Multilayer Switch for inter-VLAN routing, supported by 2960 and 2950-24PT switches to manage the server farm.
  **Routing & Edge:** Utilizes an ISR 4331 Router, Cable Modem-PT, and Cloud-PT to simulate internet connectivity.
  **Data Center & Security:** Includes five generic servers in a high-density farm and a dedicated DMZ Server to isolate public services.
  **Wireless Connectivity:** Integrated a WRT300N Wireless Router to provide mobile workstations with secure file access and service verification.

**Core Concepts & Technical Implementation**
  **Routing Protocols:** Configured Static and Default Routing to ensure efficient packet delivery across the infrastructure.

**Network Security:**
  **Extended Named ACLs:** Implemented a "secure_dc" list permitting TCP (WWW) and ICMP traffic to the server network while denying all unauthorized IP traffic.
 **DMZ:** Isolated public-facing servers from the internal data center for enhanced security.
**Layer 2 Redundancy:** Used EtherChannel with 802.1Q trunking to increase bandwidth and provide link redundancy between switches.

**Traffic Management:**
  **NAT (Network Address Translation):** Applied for public-private IP mapping.
 **VLAN Segmentation:** Configured SVI on VLAN 1 (IP: $10.0.0.1$) for logical network management.
**Wireless Services:** Setup the WRT300N as a DHCP Server (Range: $192.168.0.100 - 149$) with a Static WAN IP ($192.168.1.5$) for consistent reachability.

**Conclusion**
This project successfully simulates a functional data center capable of hosting professional web services and providing public internet access. It highlights technical proficiency in configuring multi-vendor-style environments, managing complex traffic flows, and ensuring hardware redundancy.

**Note to Professionals & Community**
This project is based on my current knowledge as a Network Engineer Trainee. I am committed to continuous learning and growth. If you identify any flaws in the architecture or configuration workflow, please reach out via message or email. I welcome the opportunity to rectify errors and improve my skills.
