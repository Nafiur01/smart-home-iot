# Smart Home IoT Network (Cisco Packet Tracer)

This project simulates a smart home network using Cisco Packet Tracer. It includes IoT devices, a local server, home gateway, and internet connectivity through a DSL modem.

## 🗂️ Files Included
- `Iot_101(new).pkt` – The main Packet Tracer project
- `Iot_101(new).png` – Network architecture diagram
- `README.md` – Project overview and instructions

## 🌐 Network Features
- IoT devices (smart light, motion detector, etc.)
- DHCP, DNS, and Web Server configurations
- Secure local server for device control
- Internet simulation using cloud ➝ DSL ➝ router

## 🧪 How to Test
1. Open `Iot_101(new).pkt` in Cisco Packet Tracer
2. Run the simulation mode to see IoT device communication
3. Access local web server via browser on tablet/PC device
4. Ping from router to test internet connectivity

### Problem & Solutions
1. Home Gateway IP is 192.168.1.3, while the Router is 192.168.0.1 — they are on two different subnets.

Solution:
Home Gateway and Router should be in the same subnet. Match Network Subnet. 

2. Home Gateway, Routers, Remote Server should not be connected wirelessly.

Solution:
Ensure wired connection between these components.

3. Always ping and trace the packet to ensure proper connection between networks

### After fixing above complications, I have successfully completed proper connection between networks.
✅ Connected the Home Gateway to the **Router's network
✅ Made sure all devices are in the **same subnet
✅ Got the Tablet and IoT devices reaching the remote IoT Server
✅ Registered devices — mission complete! 🚀
