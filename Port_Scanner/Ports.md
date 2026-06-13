# Ports

## 📌 Overview

A port is a logical communication endpoint used by applications and services to send and receive data over a network.

Ports allow multiple services to run simultaneously on the same device while using the same IP address.

---

## 🎯 Why Ports are Important

Ports help:

* Identify specific services on a device
* Enable communication between applications
* Allow multiple network connections simultaneously
* Support client-server communication

Without ports, a device would not know which application should receive incoming data.

---

## 🔹 IP Address vs Port

| IP Address                  | Port                             |
| --------------------------- | -------------------------------- |
| Identifies a device         | Identifies a service/application |
| Example: 192.168.1.10       | Example: 80                      |
| Works at the Internet Layer | Works at the Transport Layer     |

Example:

```text
192.168.1.10:80
```

* IP Address → Device
* Port 80 → HTTP service

---

## 🔹 Port Number Ranges

### Well-Known Ports (0 – 1023)

Used by common services and protocols.

Examples:

| Port   | Protocol | Service |
| ------ | -------- | ------- |
| 20, 21 | TCP      | FTP     |
| 22     | TCP      | SSH     |
| 23     | TCP      | Telnet  |
| 25     | TCP      | SMTP    |
| 53     | TCP/UDP  | DNS     |
| 80     | TCP      | HTTP    |
| 110    | TCP      | POP3    |
| 143    | TCP      | IMAP    |
| 443    | TCP      | HTTPS   |

---

### Registered Ports (1024 – 49151)

Assigned to specific applications and software.

Examples:

* MySQL (3306)
* PostgreSQL (5432)

---

### Dynamic / Ephemeral Ports (49152 – 65535)

Temporary ports used by clients for communication.

---

## 🔹 TCP and UDP Ports

### TCP Ports

TCP provides:

* Reliable communication
* Error checking
* Ordered delivery

Common TCP services:

* HTTP
* HTTPS
* SSH
* FTP

---

### UDP Ports

UDP provides:

* Faster communication
* Low overhead
* No guarantee of delivery

Common UDP services:

* DNS
* DHCP
* Streaming services

---

## 🔹 Port States

### Open Port

A service is actively listening and accepting connections.

Example:

```text
Port 80 → Open
```

---

### Closed Port

No application is listening on the port.

---

### Filtered Port

Traffic is blocked by a firewall or security device.

---

## 🌍 Real-World Applications

Ports are used in:

* Web browsing
* Email communication
* Remote access
* File transfer
* Database connections
* Network scanning

---

## ⚠️ Security Considerations

Attackers often scan ports to:

* Discover running services
* Identify vulnerabilities
* Gather information about a target

System administrators use port scanning to:

* Audit networks
* Verify services
* Detect unauthorized applications

---

## 🚀 Project Connection

### Project: Port Scanner

In the Port Scanner project, port numbers were checked to determine whether services were open or closed.

This project provided practical exposure to:

* TCP/IP networking
* Service identification
* Socket programming
* Reconnaissance techniques
* Network security fundamentals

---

## 📚 Key Takeaways

* Ports identify services and applications.
* Multiple services can run on a single device using different ports.
* Ports operate at the Transport Layer.
* Port scanning helps discover active services.
* Understanding ports is fundamental in networking and cybersecurity.

---

## 📖 References

* Computer Networking: A Top-Down Approach – Kurose & Ross
* CompTIA Network+
* TCP/IP Illustrated – W. Richard Stevens
* Nmap Documentation
