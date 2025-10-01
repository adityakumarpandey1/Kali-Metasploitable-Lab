# Networking Basics (Task 3)

## OSI Model Layers (7 Layers)

| Layer | Name | Function | Data Unit |
| :--- | :--- | :--- | :--- |
| **7** | **Application** | Provides interface for user applications. | Data |
| **4** | **Transport** | Reliable (TCP) or unreliable (UDP) data transfer. | **Segments** |
| **3** | **Network** | Routing and logical addressing (IP addresses). | **Packets** |
| **2** | **Data Link** | Physical addressing (MAC addresses) and error control. | **Frames** |
| **1** | **Physical** | Transmits raw bit stream. | Bits |

## TCP vs. UDP

* **TCP (Transmission Control Protocol):** Connection-oriented. Reliable, error-checking, guarantees delivery. Used for web, email (HTTP, SSH, FTP).
* **UDP (User Datagram Protocol):** Connectionless. Fast, no guarantee of delivery. Used for streaming, voice, and DNS queries.

## DNS and HTTP/HTTPS

* **DNS (Domain Name System):** Translates domain names (like google.com) into numerical IP addresses.
* **HTTPS:** HTTP layered over **TLS/SSL**. The **Digital Certificate** confirms the server's identity, and TLS encrypts all data transmitted.

## IP Addressing and NAT

* **Subnetting:** Dividing a large network into smaller subnets using a **Subnet Mask** (e.g., 255.255.255.0).
* **NAT (Network Address Translation):** A method used by routers to map multiple private IP addresses (like your VMs) to a single public IP.
