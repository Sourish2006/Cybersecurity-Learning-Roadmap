# Socket Programming

## 📌 Overview

Socket programming is a method of enabling communication between two devices over a network.

A socket acts as an endpoint that allows applications to send and receive data using network protocols such as TCP and UDP.

It provides the foundation for client-server communication and many networking applications.

---

## 🎯 Why Socket Programming is Important

Socket programming enables:

* Communication between devices
* Client-server architecture
* Network services and applications
* Data exchange over TCP/IP networks

Many cybersecurity tools rely heavily on socket programming.

---

## 🔹 What is a Socket?

A socket is a combination of:

```text
IP Address + Port Number
```

Example:

```text
192.168.1.10:80
```

Where:

* IP Address identifies the device.
* Port identifies the service.

---

## 🔹 Types of Sockets

### TCP Socket

Uses the Transmission Control Protocol (TCP).

Characteristics:

* Reliable communication
* Connection-oriented
* Error checking
* Ordered data delivery

Examples:

* HTTP
* HTTPS
* SSH
* FTP

---

### UDP Socket

Uses the User Datagram Protocol (UDP).

Characteristics:

* Faster communication
* Connectionless
* No guarantee of delivery

Examples:

* DNS
* DHCP
* Video streaming

---

## 🔹 Client-Server Architecture

```text
Client
   ↓
Request
   ↓
Server
   ↓
Response
```

Example:

* Browser → Web Server
* SSH Client → SSH Server

---

## 🔹 Socket Workflow

### Server Side

1. Create a socket.
2. Bind it to an IP address and port.
3. Listen for incoming connections.
4. Accept connections.
5. Send and receive data.
6. Close the socket.

---

### Client Side

1. Create a socket.
2. Connect to the server.
3. Exchange data.
4. Close the connection.

---

## 🌍 Real-World Applications

Socket programming is used in:

* Web servers
* Chat applications
* Email services
* Multiplayer games
* File transfer systems
* Network scanning tools

---

## ⚠️ Security Considerations

Attackers may use socket-based tools for:

* Port scanning
* Network reconnaissance
* Service enumeration

Defenders use socket programming for:

* Security monitoring
* Vulnerability assessment
* Network diagnostics

---

## 🚀 Project Connection

### Project: Port Scanner

In the Port Scanner project, socket programming was used to establish connections with target ports and determine whether services were open or closed.

This project provided practical experience with:

* TCP connections
* Port enumeration
* Client-server communication
* Network reconnaissance fundamentals

---

## 📚 Key Takeaways

* A socket is an endpoint for network communication.
* Socket programming enables client-server communication.
* Sockets use IP addresses and port numbers.
* TCP provides reliable communication, while UDP prioritizes speed.
* Socket programming is fundamental to networking and cybersecurity.

---

## 📖 References

* Computer Networking: A Top-Down Approach – Kurose & Ross
* TCP/IP Illustrated – W. Richard Stevens
* Python Socket Programming Documentation
* CompTIA Network+
