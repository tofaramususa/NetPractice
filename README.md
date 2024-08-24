# NetPractice

NetPractice is a project from 42 that focuses on understanding and implementing IP and TCP addressing. This project aims to provide a thorough grounding in network fundamentals, including IP addressing, subnetting, TCP/IP protocols, and related concepts. The goal is to build practical skills in network configuration and troubleshooting.

## Table of Contents
1. [Introduction](#introduction)
2. [IP Addressing](#ip-addressing)
   - [IPv4 Addressing](#ipv4-addressing)
   - [IPv6 Addressing](#ipv6-addressing)
   - [Subnetting](#subnetting)
3. [TCP/IP Protocol](#tcpip-protocol)
   - [TCP Basics](#tcp-basics)
   - [TCP Handshake](#tcp-handshake)
   - [TCP Flags](#tcp-flags)
4. [Practical Applications](#practical-applications)
5. [Resources and Tools](#resources-and-tools)
6. [Conclusion](#conclusion)

## Introduction

NetPractice is designed to enhance your understanding of IP and TCP addressing through practical exercises and real-world scenarios. The project covers essential networking concepts and prepares you for working with network configurations and troubleshooting network issues.

## IP Addressing

### IPv4 Addressing

IPv4 (Internet Protocol version 4) is the most widely used IP addressing scheme. It uses a 32-bit address format, divided into four octets. Each octet is represented as a decimal number between 0 and 255, separated by dots.

#### Example
```plaintext
192.168.1.1
```

- **Network Address**: The portion of the IP address that identifies the network segment.
- **Host Address**: The portion of the IP address that identifies a specific device within the network.

### IPv6 Addressing

IPv6 (Internet Protocol version 6) is the successor to IPv4 and uses a 128-bit address format. It provides a larger address space to accommodate the growing number of devices.

#### Example
```plaintext
2001:0db8:85a3:0000:0000:8a2e:0370:7334
```

- **Compressed Format**: Leading zeros can be omitted, and consecutive sections of zeros can be replaced with `::`.

### Subnetting

Subnetting involves dividing a network into smaller, manageable sub-networks. It improves network performance and security.

#### Calculating Subnets

1. **Determine the Number of Subnets**: Based on the subnet mask and the number of bits used for subnetting.
2. **Determine the Number of Hosts per Subnet**: Based on the remaining bits in the subnet mask.

#### Example
```plaintext
Network: 192.168.1.0/24
Subnet Mask: 255.255.255.0
```

## TCP/IP Protocol

### TCP Basics

TCP (Transmission Control Protocol) is a connection-oriented protocol that ensures reliable data transmission over a network.

- **Connection-Oriented**: Establishes a connection before data transmission.
- **Reliable**: Ensures data packets are delivered in the correct order.

### TCP Handshake

The TCP handshake is a three-step process to establish a connection between a client and server:

1. **SYN**: The client sends a synchronization request.
2. **SYN-ACK**: The server acknowledges the request and sends a synchronization acknowledgment.
3. **ACK**: The client sends an acknowledgment to the server.

### TCP Flags

TCP flags are used in the TCP header to manage the state of a connection. Common flags include:

- **SYN**: Synchronize
- **ACK**: Acknowledge
- **FIN**: Finish
- **RST**: Reset

## Practical Applications

NetPractice includes various exercises and scenarios to apply your knowledge of IP and TCP addressing. These exercises may involve:

- **Configuring IP Addresses**: Setting up static and dynamic IP addresses.
- **Subnetting Exercises**: Creating and managing subnets.
- **TCP Connections**: Simulating and analyzing TCP connections and handshakes.

## Resources and Tools

To support your learning and implementation, consider the following resources and tools:

- **Wireshark**: A network protocol analyzer for capturing and analyzing network traffic.
- **Ping**: A network utility to test connectivity between devices.
- **Traceroute**: A tool to trace the path packets take from source to destination.
- **Subnet Calculators**: Online tools to calculate subnets and network addresses.

## Conclusion

NetPractice is an essential project for understanding IP and TCP addressing. By mastering these concepts, you'll gain practical skills in network configuration and troubleshooting, preparing you for real-world network management tasks.

Explore the provided resources and tools to deepen your knowledge and enhance your practical skills in networking.

For more details, refer to the project documentation and exercises provided as part of NetPractice.
