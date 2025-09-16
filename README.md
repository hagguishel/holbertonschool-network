# Networking Basics – Project README

## 📚 Resources
Before starting this project, read or watch:
- [OSI model](https://en.wikipedia.org/wiki/OSI_model)
- [Different types of network](https://en.wikipedia.org/wiki/Computer_network)
- [LAN network](https://en.wikipedia.org/wiki/Local_area_network)
- [WAN network](https://en.wikipedia.org/wiki/Wide_area_network)
- [Internet](https://en.wikipedia.org/wiki/Internet)
- [MAC address](https://en.wikipedia.org/wiki/MAC_address)
- [What is an IP address](https://en.wikipedia.org/wiki/IP_address)
- [Private and public address](https://en.wikipedia.org/wiki/Private_network)
- [IPv4 and IPv6](https://en.wikipedia.org/wiki/IP_version_6)
- [Localhost](https://en.wikipedia.org/wiki/Localhost)
- [TCP and UDP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
- [TCP/UDP ports list](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
- [What is ping / ICMP](https://en.wikipedia.org/wiki/Ping_(networking_utility))
- [Positional parameters](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_09_07.html)

### 🔧 man or help pages:
- `netstat`
- `ping`

---

## 🎯 Learning Objectives
By the end of this project, you should be able to **explain to anyone, without Google**:

### 🌐 OSI Model
- What the OSI model is
- How many layers it has
- How it is organized

### 🖧 Networks
- What is a LAN
  - Typical usage
  - Typical geographical size
- What is a WAN
  - Typical usage
  - Typical geographical size
- What is the Internet

### 🏷 IP Addressing
- What an IP address is
- The 2 types of IP addresses (private vs public)
- What localhost is
- What a subnet is
- Why IPv6 was created

### 📡 TCP / UDP
- The 2 main data transfer protocols used by IP (transfer layer in the OSI model)
- Main difference between TCP and UDP
- What a port is
- Memorize the port numbers for:
  - SSH → `22`
  - HTTP → `80`
  - HTTPS → `443`
- Tool/protocol used to check if a device is connected to a network (ping/ICMP)

---

## ✅ Requirements

### 🖥 Bash Script Files
- Allowed editors: `vi`, `vim`, `emacs`
- Your scripts will be interpreted on **Ubuntu 22.04**
- All files must end with a **new line**
- You must have a `README.md` at the root of the project
- All scripts must be **executable**
- Your Bash scripts must pass `shellcheck` without errors
- The first line of all Bash scripts must be:
  ```bash
  #!/usr/bin/env bash
