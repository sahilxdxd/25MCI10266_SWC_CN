# Learning Summary 🚀

I have completed the basic concepts of Computer Networks. This helped me understand how devices communicate, how data moves across a network, and how important networking tools and protocols work together.

## Topics Covered

* Computer Networks Basics
* Networking Devices
* OSI Model
* IPv4 Addressing
* TCP and UDP Protocols
* DNS (Domain Name System)
* Subnetting
* IP Address Classes

---

# Computer Networks

## Introduction

A computer network is a group of connected devices that share data, resources, and information. It can work through wired or wireless connections.

## Why Computer Networks Are Used

They make communication faster and easier. Networks help users share files, access the internet, and use shared devices like printers.

## Examples of Computer Networks

* Internet
* Home Wi-Fi
* Office network
* Mobile network

## Types of Computer Networks

### 1. LAN (Local Area Network)

A LAN connects devices in a small area like a home, school, or office. It provides high-speed communication.

### 2. MAN (Metropolitan Area Network)

A MAN connects multiple networks within a city or metropolitan area.

### 3. WAN (Wide Area Network)

A WAN connects devices across large geographical regions. The Internet is the largest WAN.

## Components of Computer Networks

* **Router:** Connects different networks.
* **Switch:** Connects devices within the same network.
* **Server:** Provides resources and services.
* **Client:** Requests services from a server.
* **Network Cable:** Used for wired communication.

## Advantages

* Easy data sharing
* Fast communication
* Resource sharing
* Better management
* Internet access

## Disadvantages

* Security threats
* Network failures affect many users
* Requires maintenance
* Malware can spread quickly

## Conclusion

Computer networks are essential for modern communication and information exchange.

---

# Networking Devices

Networking devices are hardware components that help establish communication between computers and other networked devices.

## Common Networking Devices

### 1. Router

Routes data between different networks and the internet.

### 2. Switch

Connects devices within the same network efficiently.

### 3. Hub

Broadcasts data to all connected devices.

### 4. Modem

Connects a local network to an internet service provider.

### 5. Repeater

Boosts weak network signals over long distances.

## Conclusion

Networking devices ensure smooth and reliable communication across networks.

---

# OSI Model (Open Systems Interconnection)

## Introduction

The OSI Model is a conceptual framework that explains how network communication occurs through seven layers.

## OSI Layers

| Layer | Name         | Main Function          |
| ----- | ------------ | ---------------------- |
| 7     | Application  | User services          |
| 6     | Presentation | Formatting, encryption |
| 5     | Session      | Session management     |
| 4     | Transport    | Reliable delivery      |
| 3     | Network      | Routing and addressing |
| 2     | Data Link    | Error detection        |
| 1     | Physical     | Data transmission      |

## Layers of OSI Model

### 1. Physical Layer

Transfers raw bits through physical media.

**Examples:** Cables, Hubs, Repeaters

### 2. Data Link Layer

Handles communication between devices on the same network.

**Examples:** Switches, MAC Addresses

### 3. Network Layer

Determines the path for data transfer.

**Examples:** Routers, IP Addresses

### 4. Transport Layer

Ensures proper delivery of data.

**Examples:** TCP, UDP

### 5. Session Layer

Creates and manages communication sessions.

**Examples:** Video meetings, Login sessions

### 6. Presentation Layer

Handles encryption, translation, and compression.

**Examples:** JPEG, MPEG, SSL

### 7. Application Layer

Provides network services directly to users.

**Examples:** Browsers, Email, FTP

## Advantages of OSI Model

* Easy troubleshooting
* Better understanding of networking
* Standardized communication
* Modular design

## Conclusion

The OSI Model simplifies networking by dividing communication into seven layers.

---

# IPv4 (Internet Protocol Version 4)

## Introduction

IPv4 is a protocol used to identify devices and enable communication over networks.

## IPv4 Address Format

IPv4 uses a **32-bit address** divided into four octets.

**Example:**

```text
192.168.1.10
```

## How IPv4 Works

Every device receives a unique IP address that helps send and receive data correctly.

## Classes of IPv4 Address

| Class | Usage           |
| ----- | --------------- |
| A     | Large Networks  |
| B     | Medium Networks |
| C     | Small Networks  |
| D     | Multicasting    |
| E     | Research        |

## Types of IPv4 Address

### Public IP Address

Used on the internet.

### Private IP Address

Used within local networks.

## Advantages

* Widely supported
* Easy configuration
* Reliable communication

## Limitations

* Limited address space
* Lower security compared to IPv6

## Conclusion

IPv4 remains one of the most widely used networking protocols.

---

# TCP and UDP

## Introduction

TCP and UDP are transport layer protocols used for communication between devices.

---

## TCP (Transmission Control Protocol)

### What is TCP?

TCP is a connection-oriented protocol that ensures reliable data delivery.

### Features of TCP

* Reliable communication
* Error checking
* Ordered delivery
* Retransmission of lost packets

### Examples

* HTTPS
* Email
* File Transfer
* Online Banking

---

## UDP (User Datagram Protocol)

### What is UDP?

UDP is a connectionless protocol focused on speed.

### Features of UDP

* Fast communication
* Low latency
* Lightweight
* No retransmission

### Examples

* Online Gaming
* Live Streaming
* Voice Calls
* Video Conferencing

---

## Difference Between TCP and UDP

| Feature        | TCP        | UDP            |
| -------------- | ---------- | -------------- |
| Connection     | Required   | Not Required   |
| Speed          | Slower     | Faster         |
| Reliability    | High       | Low            |
| Error Checking | Yes        | Basic          |
| Order          | Maintained | Not Guaranteed |

## Conclusion

TCP prioritizes reliability, while UDP prioritizes speed.

---

# DNS (Domain Name System)

## Introduction

DNS converts domain names into IP addresses, making websites easier to access.

**Example:**

```text
google.com → 142.250.195.100
```

## Why DNS is Needed

Humans remember names more easily than numbers, so DNS simplifies internet usage.

## How DNS Works

1. User enters a domain name.
2. DNS Resolver receives the request.
3. DNS Servers locate the IP address.
4. Browser connects to the website.

## Types of DNS Servers

### 1. DNS Resolver

Processes user requests.

### 2. Root DNS Server

Directs requests to the correct TLD server.

### 3. TLD Server

Handles extensions like `.com`, `.org`, and `.net`.

### 4. Authoritative DNS Server

Stores actual DNS records.

## Common DNS Records

| Record | Purpose          |
| ------ | ---------------- |
| A      | IPv4 Mapping     |
| AAAA   | IPv6 Mapping     |
| CNAME  | Alias            |
| MX     | Mail Server      |
| TXT    | Text Information |

## Advantages

* Easy website access
* Faster browsing
* Supports email systems

## Real Life Example

Remembering `google.com` is easier than remembering an IP address.

## Conclusion

DNS acts as the internet's phonebook by converting names into IP addresses.

---

# Subnetting

## Introduction

Subnetting divides a large network into smaller subnetworks.

## Why Subnetting is Needed

* Reduces traffic
* Improves security
* Saves IP addresses
* Simplifies management

## Basic Concept of Subnetting

Every IP address contains:

* Network Portion
* Host Portion

**Example:**

```text
192.168.1.10
```

Network: `192.168.1`

Host: `10`

## How Subnetting Works

A large network is divided into multiple smaller networks for better control.

## Subnet Mask

Separates the network and host portions.

**Example:**

```text
255.255.255.0
```

## CIDR Notation

CIDR indicates the number of network bits.

**Example:**

```text
192.168.1.0/24
```

## Common Subnet Masks

| CIDR | Subnet Mask   |
| ---- | ------------- |
| /8   | 255.0.0.0     |
| /16  | 255.255.0.0   |
| /24  | 255.255.255.0 |
| /32  | Single Host   |

## Example

A network `192.168.1.0/24` can be divided into smaller `/26` subnetworks.

## Advantages

* Efficient IP usage
* Better performance
* Improved security
* Easier troubleshooting

## Real Life Example

Different college departments can have separate subnets.

## Conclusion

Subnetting helps organize and secure networks effectively.

---

# IP Address Classes

## Introduction

IPv4 addresses are divided into five classes based on network size and purpose.

## Types of Address Classes

### Class A

* Range: `1.0.0.0 – 126.255.255.255`
* Subnet Mask: `255.0.0.0`
* Used for large networks

### Class B

* Range: `128.0.0.0 – 191.255.255.255`
* Subnet Mask: `255.255.0.0`
* Used for medium networks

### Class C

* Range: `192.0.0.0 – 223.255.255.255`
* Subnet Mask: `255.255.255.0`
* Used for small networks

### Class D

* Range: `224.0.0.0 – 239.255.255.255`
* Used for multicasting

### Class E

* Range: `240.0.0.0 – 255.255.255.255`
* Used for research and testing

## Address Classes Table

| Class | Range   | Usage           |
| ----- | ------- | --------------- |
| A     | 1–126   | Large Networks  |
| B     | 128–191 | Medium Networks |
| C     | 192–223 | Small Networks  |
| D     | 224–239 | Multicast       |
| E     | 240–255 | Research        |

## Easy Way to Remember

* A → All Big Networks
* B → Business Networks
* C → Common Users
* D → Data Multicast
* E → Experimental

## Conclusion

IP classes help organize IPv4 addresses according to different network requirements.
