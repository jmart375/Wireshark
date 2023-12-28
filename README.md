# Wireshark 

## Overview

Wireshark is a powerful open-source network protocol analyzer. It allows you to capture and analyze the data traveling back and forth on your network in real-time. With support for hundreds of protocols, Wireshark is an essential tool for network administrators, security professionals, and developers.

## Features

- **Packet Capture:** Capture live data from a network interface or read from previously captured files.
- **Protocol Support:** Analyze a wide range of protocols, including TCP, UDP, IP, HTTP, DNS, and more.
- **Live Packet Filtering:** Apply filters to capture specific types of packets or traffic patterns.
- **Deep Inspection:** Dive into the details of each packet, including header and payload information.
- **Colorized Packet Views:** Easily distinguish between different types of packets with color-coded views.
- **Cross-Platform:** Available for Windows, macOS, and various Linux distributions.

## Getting Started

1. **Open Wireshark:** Launch the application on your system.
2. **Choose Capture Interface:** Select the network interface for packet capture.
3. **Start Capturing:** Click on the "Start" button to begin capturing packets.
4. **Apply Filters:** Optionally, apply filters to focus on specific types of traffic.
5. **Analyze Packets:** Explore captured packets using the intuitive interface.

## Usage Examples

### Capturing HTTP Traffic

```bash
wireshark -i <interface> -f "port 80"

```

### Filtering by IP Address
```bash
wireshark -i <interface> -f "host <ip_address>"
```

### Snapshots
![windows 129](https://github.com/jmart375/Wireshark/assets/91294710/5dc02ba8-0181-4352-90fe-fb4a0f88a347)

![windows 157](https://github.com/jmart375/Wireshark/assets/91294710/8ad07d3b-9d23-4c0b-8b6a-23db61352ac5)

