# 🌐 TCP/IP Model (Transmission Control Protocol / Internet Protocol)

The TCP/IP model is a framework that explains how data is transmitted over the internet.

It is simpler than the OSI model and widely used in real-world networking.

---

## 📊 TCP/IP Layers

| Layer | Description |
|------|------------|
| Application | User interaction (HTTP, DNS, FTP) |
| Transport | Data transfer (TCP, UDP) |
| Internet | IP addressing & routing |
| Network Access | Physical transmission (hardware, MAC) |

---

## 🧱 1. Application Layer

Handles user-level protocols.

Examples:
- HTTP / HTTPS (web browsing)
- DNS (domain resolution)
- FTP (file transfer)

---

## 🔄 2. Transport Layer

Responsible for data delivery between devices.

Protocols:
- TCP → Reliable, connection-based
- UDP → Fast, connectionless

---

## 🌍 3. Internet Layer

Handles logical addressing and routing.

Protocol:
- IP (Internet Protocol)

Functions:
- Assign IP addresses
- Route packets across networks

---

## 🔌 4. Network Access Layer

Handles physical transmission of data.

Includes:
- MAC addresses
- Ethernet
- Hardware (cables, switches)

---

## 📦 Data Flow (Simple)

Application → Transport → Internet → Network Access → Destination

---

## 🛡 Why TCP/IP Model is Important for SOC?

- Helps analyze network traffic
- Understand where attacks happen
- Identify suspicious packets
- Helps in log analysis

---

## 📌 Example

Opening a website:
- Application → HTTP request
- Transport → TCP connection
- Internet → IP routing
- Network Access → Data sent via network

---

## ✅ Summary

TCP/IP model has 4 layers that define how data travels across networks and is essential for understanding cyber attacks.
