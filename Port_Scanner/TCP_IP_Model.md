# TCP/IP Model

## 📌 Overview

The TCP/IP (Transmission Control Protocol/Internet Protocol) model is a set of communication protocols used to connect devices over a network.

It provides the foundation for communication on the Internet and most modern computer networks.

---

## 🎯 Purpose

The TCP/IP model defines how data is:

* Created
* Addressed
* Transmitted
* Routed
* Received

between devices on a network.

---

## 🔹 Layers of the TCP/IP Model

| Layer          | Function                                    | Protocols             |
| -------------- | ------------------------------------------- | --------------------- |
| Application    | Provides services to users and applications | HTTP, HTTPS, FTP, DNS |
| Transport      | End-to-end communication and reliability    | TCP, UDP              |
| Internet       | Logical addressing and routing              | IP, ICMP              |
| Network Access | Physical transmission of data               | Ethernet, Wi-Fi       |

---

## 🔹 Data Encapsulation

```text
Application Layer
        ↓
Transport Layer
        ↓
Internet Layer
        ↓
Network Access Layer
```

Data travels down the layers before transmission and moves up the layers when received.

---

## 🌍 Real-World Applications

The TCP/IP model is used in:

* Internet communication
* Web browsing
* Email services
* File transfer
* Network scanning tools

---

## 🚀 Project Connection

### Project: Port Scanner

Understanding the TCP/IP model is essential for port scanning because:

* Ports belong to the Transport Layer.
* TCP and UDP protocols determine communication.
* IP addresses operate at the Internet Layer.
* Socket programming relies on TCP/IP protocols.

---

## 📚 Key Takeaways

* TCP/IP is the foundation of modern networking.
* It consists of four layers.
* TCP and UDP operate at the Transport Layer.
* Port scanners depend heavily on TCP/IP concepts.
* Understanding TCP/IP is essential in cybersecurity.

---

## 📖 References

* Computer Networking: A Top-Down Approach – Kurose & Ross
* CompTIA Network+
* TCP/IP Illustrated – W. Richard Stevens
