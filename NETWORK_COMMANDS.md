#### ** Linux Networking Commands**

| **Command** | **Purpose** |
|-------------|-------------|
| `ifconfig` | View or configure network interfaces (older tool) |
| `ip a` | Display all IP addresses and interfaces (modern replacement for `ifconfig`) |
| `ping` | Test network connectivity to a host |
| `traceroute` | Trace the path packets take to reach a destination |
| `netstat -tuln` | Show active listening ports and connections |
| `ss -tuln` | Display socket statistics (faster alternative to `netstat`) |
| `dig` | Perform DNS lookup for a domain |
| `nslookup` | Query internet name servers (DNS) |
| `curl` | Transfer data to/from server (HTTP, FTP, etc.) |
| `wget` | Download files from the web |
| `hostname` | Show or set the system hostname |
| `nmap` | Scan network for open ports and services |
| `arp -a` | Display IP to MAC address mappings |
| `ip route` | Show or manipulate the routing table |
| `nc` / `netcat` | Open TCP/UDP connections, useful for debugging |
| `tcpdump` | Capture and analyze network packets |
| `ethtool` | Display or change Ethernet device settings |

---

**1. View network interfaces (IP, MAC, etc.)**
```bash
ifconfig
ip a
```

**2. Test network connectivity**
```bash
ping google.com
```

**3. Trace route to a host**
```bash
traceroute google.com
```

**4. Show active ports and connections**
```bash
netstat -tuln
ss -tuln
```

**5. DNS lookup**
```bash
dig example.com
nslookup example.com
```

**6. Transfer or download files**
```bash
curl https://example.com
wget https://example.com/file.zip
```

**7. View hostname**
```bash
hostname
```

**8. Scan network for open ports**
```bash
nmap 192.168.1.1
```

**9. Show ARP table**
```bash
arp -a
```

**10. View routing table**
```bash
ip route
```

**11. Open a simple TCP listener**
```bash
nc -l -p 8080
```

**12. Capture packets on an interface**
```bash
tcpdump -i eth0
```

**13. View Ethernet settings**
```bash
ethtool eth0
```
----