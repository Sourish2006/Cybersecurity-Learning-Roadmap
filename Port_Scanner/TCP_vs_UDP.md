# TCP vs UDP

## 📌 Overview

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two transport layer protocols used in the TCP/IP model.

Both protocols enable communication between devices, but they differ in reliability, speed, and use cases.

---

## 🎯 Purpose

Transport layer protocols are responsible for:

* End-to-end communication
* Data transmission between applications
* Port addressing
* Error handling and reliability

---

## 🔹 TCP (Transmission Control Protocol)

TCP is a connection-oriented protocol that ensures reliable communication.

### Characteristics

* Connection-oriented
* Reliable communication
* Error checking
* Ordered delivery of data
* Retransmission of lost packets

### Advantages

* High reliability
* Data integrity
* Guaranteed delivery

### Disadvantages

* Slower than UDP
* Higher overhead

### Common TCP Services

| Port  | Service |
| ----- | ------- |
| 20,21 | FTP     |
| 22    | SSH     |
| 23    | Telnet  |
| 25    | SMTP    |
| 80    | HTTP    |
| 443   | HTTPS   |

---

## 🔹 UDP (User Datagram Protocol)

UDP is a connectionless protocol that prioritizes speed over reliability.

### Characteristics

* Connectionless
* Faster communication
* Low overhead
* No error recovery
* No guarantee of delivery

### Advantages

* High speed
* Lower latency
* Efficient for real-time applications

### Disadvantages

* Unreliable transmission
* Possible packet loss

### Common UDP Services

| Port  | Service |
| ----- | ------- |
| 53    | DNS     |
| 67,68 | DHCP    |
| 69    | TFTP    |
| 123   | NTP     |

---

## 🔹 Comparison

| Feature         | TCP                 | UDP            |
| --------------- | ------------------- | -------------- |
| Connection      | Connection-oriented | Connectionless |
| Reliability     | High                | Low            |
| Speed           | Slower              | Faster         |
| Error Checking  | Yes                 | Minimal        |
| Packet Ordering | Guaranteed          | Not guaranteed |
| Overhead        | Higher              | Lower          |

---

## 🌍 Real-World Applications

### TCP

Used in:

* Web browsing
* Email services
* File transfer
* Remote access

### UDP

Used in:

* DNS
* Online gaming
* Video streaming
* Voice over IP (VoIP)

---

## ⚠️ Security Considerations

Attackers may exploit both TCP and UDP services during:

* Port scanning
* Service enumeration
* Reconnaissance activities

Security professionals use TCP and UDP analysis for:

* Vulnerability assessments
* Network monitoring
* Threat detection

---

## 🚀 Project Connection

### Project: Port Scanner

The Port Scanner project primarily used TCP connections to determine whether a port was open or closed.

Understanding TCP and UDP helped explain:

* Why some ports respond differently.
* Why TCP scanning is more reliable.
* How services communicate over networks.

---

## 📚 Key Takeaways

* TCP and UDP operate at the Transport Layer.
* TCP prioritizes reliability, while UDP prioritizes speed.
* TCP uses connections; UDP does not.
* Different services use different protocols.
* Understanding TCP and UDP is essential for networking and cybersecurity.

---

## 📖 References

* Computer Networking: A Top-Down Approach – Kurose & Ross
* TCP/IP Illustrated – W. Richard Stevens
* CompTIA Network+
* RFC 793 (TCP)
* RFC 768 (UDP)
