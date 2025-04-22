#  Linux Networking Commands 

##  Prerequisites - Tools Installation

Before using some networking commands, install the necessary packages:

```bash
sudo apt update
sudo apt install net-tools dnsutils traceroute nmap curl wget tcpdump ethtool iproute2 netcat-openbsd
```

---

##  Basic Network Information

| Command | Description |
|---------|-------------|
| `ifconfig` | Displays network interface configuration (IP, MAC, etc.) |
| `ip a` | Shows all IP addresses and interfaces (modern alternative to ifconfig) |
| `hostname` | Displays or sets the system hostname |
| `ip route` | Shows/manipulates routing table |
| `arp -a` | Displays ARP table (IP ↔ MAC mapping) |
| `ethtool [interface]` | Displays/modifies Ethernet device settings |

---

##  Connectivity Testing

| Command | Description |
|---------|-------------|
| `ping [host]` | Tests reachability of a host |
| `traceroute [host]` | Traces the path to a destination host |
| `mtr [host]` | Real-time combination of ping and traceroute |
| `nc [host] [port]` | Tests if a specific port is open |
| `telnet [host] [port]` | Basic port testing (less secure, legacy) |

---

##  DNS and Domain Tools

| Command | Description |
|---------|-------------|
| `nslookup [domain]` | Performs DNS lookup |
| `dig [domain]` | Provides detailed DNS query info |

---

##  Remote Access and Transfer

| Command | Description |
|---------|-------------|
| `ssh [user]@[host]` | Secure remote login |
| `curl [URL]` | Transfers data from/to a URL (HTTP, FTP, etc.) |
| `wget [URL]` | Downloads files from the web |

---

## 🔍 Port and Service Scanning

| Command | Description |
|---------|-------------|
| `netstat -tuln` | Displays all active ports and connections |
| `ss -tuln` | Faster alternative to netstat for socket statistics |
| `nmap [IP]` | Scans for open ports and services |

---

##  Packet Inspection and Capturing

| Command | Description |
|---------|-------------|
| `tcpdump -i [interface]` | Captures network packets |
| `tshark -i [interface]` | CLI version of Wireshark |

---

##  Interface & Wireless Configuration

| Command | Description |
|---------|-------------|
| `iwconfig` | Configures wireless interfaces (SSID, mode, etc.) |

---

## 🛠 Configuration and Scripting (Windows/Linux)

| Command | Description |
|---------|-------------|
| `netsh interface ip show config` (Windows) | Shows IP configuration |
| `route -n` | Displays routing table in numeric format |

---

##  Listening and Port Forwarding

| Command | Description |
|---------|-------------|
| `nc -l -p [port]` | Starts a TCP listener on the specified port |

---

##  Example Usage

```bash
# View all interfaces
ip a

# Test connectivity
ping google.com

# Trace packet route
traceroute example.com

# DNS query
nslookup openai.com

# Download a file
wget https://example.com/file.zip

# Scan for open ports
nmap 192.168.0.1

# Capture packets
sudo tcpdump -i eth0
```

---

---


