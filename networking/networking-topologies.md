# 🖧 Network Topologies

Network topology = the **physical or logical arrangement** of nodes and links.  
Different topologies affect **cost, performance, and reliability**.

---

## 1️⃣ Bus Topology
- All devices connected to a single cable (the bus).  
- Data transmitted over the bus, and every device checks if data is intended for it.  

✅ Simple to implement.  
❌ Not very reliable (difficult to troubleshoot, not scalable).  

- Example: Older Ethernet networks using coaxial cables.  

---

## 2️⃣ Star Topology
- All devices connected to a **central hub or switch**.  
- Data is sent from device → hub/switch → recipient.  

✅ More reliable than bus.  
✅ Easy to manage and troubleshoot.  
❌ If the hub/switch fails, the whole network is affected.  

- Example: Modern Ethernet networks using switches.  

---

## 3️⃣ Ring Topology
- Devices connected in a **closed loop**.  
- Data transmitted in a circular manner; each device checks destination address.  

✅ More reliable than bus topology.  
✅ Data can travel in either direction (fault tolerance).  
❌ Complex to configure and maintain.  

- Example: Token Ring networks (legacy).  

---

## 4️⃣ Mesh Topology
- Each device connected to multiple devices.  
- Provides redundancy and high availability (multiple paths).  

✅ Very reliable & fault tolerant.  
✅ Common in critical infrastructure (e.g., Internet backbone).  
❌ Expensive, complex.  

- Example: Internet backbone with redundant routers.  

---

## 5️⃣ Hybrid Topology
- Combines 2 or more topologies.  
- Flexible and adaptable to different needs.  

- Example: Star topology for departments + bus topology for inter-department connection.  

---

# 📘 Network Protocols
Protocols define:  
- The **format of data packets**  
- **Addressing schemes** used to identify devices  
- Procedures for **error detection and correction**

---

## 🌐 TCP/IP (Transmission Control Protocol / Internet Protocol)
- Foundation of the Internet.  
- Suite of protocols that define how data is transmitted.  

### 🔹 Key Features
- **TCP**: Reliable, connection-oriented communication.  
- **IP**: Provides addressing and routing.  

✅ Ensures reliable data delivery.  
✅ Supports applications like web browsing, email, file transfer.  
