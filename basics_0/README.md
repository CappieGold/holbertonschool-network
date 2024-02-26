# Networking basics #0

## Learning Objectives

At the end of this project, you are expected to be able to `explain to anyone`, without the help of Google:

### OSI Model
- What it is
- How many layers it has
- How it is organized

### What is a LAN
- Typical usage
- Typical geographical size

### What is a WAN
- Typical usage
- Typical geographical size

### What is the Internet
- What is an IP address
- What are the 2 types of IP address
- What is localhost
- What is a subnet
- Why IPv6 was created

### TCP/UDP
- What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
- What is the main difference between TCP and UDP
- What is a port
- Memorize SSH, HTTP and HTTPS port numbers
- What tool/protocol is often used to check if a device is connected to a network

## Answer to learning objectives

### OSI Model

#### What It Is
- The OSI (Open Systems Interconnection) model is a conceptual framework used to understand network interactions. It divides communication functions into abstract layers, facilitating the standardization of communication protocols and promoting interoperability across different systems.

#### Number of Layers
There are seven layers in the OSI model:
- Physical Layer
- Data Link Layer
- Network Layer
- Transport Layer
- Session Layer
- Presentation Layer
- Application Layer

#### Organization
Each layer deals with a specific aspect of network communication, ranging from physical cables and electrical signals (physical layer) to application interactions (application layer).

### LAN (Local Area Network)
- `Typical Usage`: Used to connect computers and devices within a geographically confined area, such as a home, office, or school building.
- `Typical Geographical Size`: Generally confined to a small geographical area.

### WAN (Wide Area Network)
- `Typical Usage`: Connects computers over large geographical distances, enabling communication between different offices of a company or between different companies.
- `Typical Geographical Size`: Can extend over large distances, sometimes even globally.

### Internet
- `What It Is`: A unique numeric address assigned to every device on a network to enable identification and communication.
- `The 2 Types`: IPv4 (32-bit) and IPv6 (128-bit).

### Localhost
- `What It Is`: A loopback address that refers to the local device. It is typically mapped to the IP address 127.0.0.1 in IPv4.

### Subnet
- `What It Is`: A subdivision of an IP network that allows a large network to be segmented into several smaller networks for improved management and security.

### Why IPv6 Was Created
- `Main Reason`: To address the depletion of IPv4 addresses. IPv6 offers a significantly larger addressing space.

### TCP/UDP
- `Main Data Transfer Protocols`: TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are the two primary protocols used for data transfer on the Internet.
- `Main Difference`: TCP is connection-oriented and ensures data delivery, whereas UDP is connectionless and does not guarantee delivery.

### Port
- `What It Is`: A number used to identify specific applications and services on a network.

### Port Numbers to Memorize
- `SSH`: Port 22
- `HTTP`: Port 80
- `HTTPS`: Port 443

### Tool/Protocol for Checking Connectivity
- `Ping`: A tool often used to check if a device is connected to a network. It uses the ICMP protocol to send echo messages to the target host and waits for a response.

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- All your Bash script files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass `shellcheck` without any error
- The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all your Bash scripts should be a comment explaining what is the script doing