# Day 3 - Networking Fundamentals in The cyber mentor yt channel

## What is a Network?
A network is a group of devices connected to share data and resources.

Examples:
- Computers
- Mobile phones
- Servers
- Routers

---

## IP Address
An IP address is a unique number that identifies a device on a network.

Example:
- 192.168.1.10

Types:
- IPv4 (most common)
- IPv6 (newer)

Private IP ranges:
- 192.168.x.x
- 10.x.x.x
- 172.16.x.x – 172.31.x.x

---

## MAC Address
A MAC address is a physical hardware address of a network card.

- Assigned by manufacturer
- Used inside local networks
- Looks like: 00:1A:2B:3C:4D:5E

---

## Port Numbers
Ports identify specific services on a device.

Common ports:
- 80   → HTTP
- 443  → HTTPS
- 22   → SSH
- 21   → FTP
- 25   → SMTP
- 3389 → RDP

IP + Port = Specific service

Example:
192.168.1.10:22 (SSH service)

---

## TCP vs UDP

TCP (Transmission Control Protocol):
- Reliable
- Connection-based
- Slower
- Used for: Web, Email, SSH

UDP (User Datagram Protocol):
- Fast
- No connection
- Less reliable
- Used for: Streaming, DNS, Gaming

---

## 3-Way Handshake (TCP)
How TCP creates a connection:

1. SYN   → Client asks to connect
2. SYN-ACK → Server accepts
3. ACK   → Client confirms

Connection is established.

---

## OSI Model (7 Layers)

1. Physical    – Cables, signals
2. Data Link   – MAC addresses
3. Network     – IP addresses
4. Transport   – TCP/UDP
5. Session     – Session control
6. Presentation– Encryption, format
7. Application – HTTP, FTP, SMTP

Hackers use OSI model to understand where attacks happen.

---

## What is a Service?
A service is a program listening on a port.

Example:
- SSH service on port 22
- Web server on port 80

---

## Nmap (Basic Idea)
Nmap is a tool used to scan:
- Open ports
- Running services
- Target information

Example:
nmap 192.168.1.10

---

## Why Networking is Importants
Networking:
- You can scan targets
- You can understand traffic
- You can find open services
- You can exploit vulnerabilities
