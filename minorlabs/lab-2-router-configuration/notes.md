# Lab 02: Router Configuration with LANs

Objective:
Set up two separate LANs, each with 2 PCs and a switch. Connect both LANs to a single router, assign proper IP addressing, configure the router interfaces, and verify connectivity between devices across both LANs.

Cisco Packet Tracer Equipment:
- 1 Router
- 2 Switches
- 4 PCs (2 per LAN)
- 6 Ethernet cables (Straight-through)
- Text and Circles (Optional, but recommend for organizing)

Network Design:
- LAN 1
  - Switch0
   - PC0 – IP: 192.168.1.10/24, Gateway: 192.168.1.1
   - PC1 – IP: 192.168.1.11/24, Gateway: 192.168.1.1
   - Configure IPs of PCs and Gateway via Static Routing

- LAN 2
  - Switch1
   - PC2 – IP: 192.168.2.10/24, Gateway: 192.168.2.1
   - PC3 – IP: 192.168.2.11/24, Gateway: 192.168.2.1
   - Configure IPs of PCs and Gateway via Static Routing

 - Router
   - Gig0/0 – IP: 192.168.1.1/24 (connects to Switch 1)
   - Gig0/1 – IP: 192.168.2.1/24 (connects to Switch 2)
   - Ensure that both ports on the router are turned on

In order to access files with the extention of pkz, download cisco packet tracer. From there, you open the pkt file in cisco packet tracer to observe its contents.


