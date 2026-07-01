# Wireshark-Network-Analysis
Cybersecurity project focused on network traffic monitoring and packet analysis using Wireshark, including DNS, TCP, TLS, and ICMP traffic inspection.


# Network Traffic Analysis Using Wireshark

## Introduction

This project demonstrates the use of Wireshark to capture and analyze network traffic. The objective was to observe common network protocols, understand communication patterns, and identify security-relevant information from captured packets.

## Tools Used

* Wireshark
* Windows 11
* Google Chrome

## Methodology

Network traffic was captured on the active Wi-Fi interface while browsing websites and generating ICMP traffic using the ping command.

The following protocols were analyzed:

* DNS
* HTTP
* HTTPS/TLS
* TCP
* ICMP

## Findings

### DNS Analysis

DNS queries were observed for multiple domains. Responses contained corresponding IP addresses returned by the configured DNS server.

### TCP Analysis

Several TCP three-way handshakes were identified. Connections were established using SYN, SYN-ACK, and ACK packets before data transfer began.

### HTTPS/TLS Analysis

Encrypted traffic was observed between the workstation and external servers. TLS handshakes confirmed secure communication channels.

### ICMP Analysis

Echo Requests and Echo Replies were successfully exchanged with external hosts, demonstrating network connectivity.

## Security Observations

* Most web traffic was encrypted using TLS.
* DNS traffic revealed websites visited by the user.
* TCP handshakes confirmed normal connection establishment behavior.
* No obvious malicious traffic was identified during the capture period.

## Conclusion

Wireshark provides detailed visibility into network communications and is an essential tool for network troubleshooting and cybersecurity investigations. This project demonstrated practical packet analysis techniques and reinforced understanding of common networking protocols.
