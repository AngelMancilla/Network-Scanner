# Network Scanner in Python

This Python-based network scanner allows you to discover devices connected to a local network by using the ARP (Address Resolution Protocol). The tool sends ARP requests to the devices in the network and receives their IP and MAC addresses in return.

## How it works

The network scanner works by broadcasting ARP requests to a target range of IP addresses in the local network. When devices respond to the ARP requests, the tool extracts their IP and MAC addresses and displays them in a structured format.

### Key Features

- Scans a range of IP addresses in the local network.
- Retrieves both IP and MAC addresses of active devices.
- Uses the ARP protocol to discover devices, even if ICMP (ping) is blocked.
- Simple and effective way to map devices on your network.

## Prerequisites

Make sure you have Python and the required dependencies installed:

1. **Python 3**: The script runs on Python 3.
2. **Scapy**: The script uses the `scapy` library for ARP requests.

Install the required dependencies using `pip`:
```bash
pip install scapy
