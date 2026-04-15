# network-security-analysis-lab
Network traffic analysis and reconnaissance using Wireshark, Nmap, ARP, and tcpdump

[Assessing the Network with Common Security Tools (3e).pdf](https://github.com/user-attachments/files/26760716/Assessing.the.Network.with.Common.Security.Tools.3e.pdf)

**🌐** Network Security Analysis Lab****
📌 Objective

This project demonstrates hands-on network analysis and reconnaissance using industry-standard tools to identify hosts, analyze traffic, and detect potential vulnerabilities.

_**🧰 Tools Used**_
- Wireshark
- Nmap / Zenmap
- Tcpdump
- Hping3
- ARP, Ping, Ipconfig / Ifconfig

🧪** Lab Overview**

This lab involved analyzing both Local Area Network (LAN) and Wide Area Network (WAN) environments using multiple virtual machines and security tools.

_Key systems included:_

- Windows & Linux hosts
- Kali Linux (attack machine)
- pfSense firewall
- Internal and external network segments

**_Key Activities_**
🛡️ _Network Enumeration_
Identified IP addresses, MAC addresses, and subnet masks using ipconfig, ifconfig, and ARP
Mapped network devices and relationships

_**📡 Traffic Analysis**_
- Captured and analyzed packets using Wireshark
- Applied filters (ICMP, ARP) to isolate relevant traffic
- Observed packet structures and communication patterns

_**⚔️ Network Scanning**_
- Conducted scans using Nmap/Zenmap (Ping, Regular, Intense scans)
- Identified open ports and running services
- Compared scan types and traffic differences

_**🧠 Packet-Level Investigation**_
- Used tcpdump to capture packet exchanges
- Observed ICMP communication and ARP requests/replies
- Analyzed TCP three-way handshake (SYN, SYN-ACK, ACK)

_**🔓 Reconnaissance Techniques**_
- Performed port probing and service enumeration
- Conducted banner grabbing using Telnet
- Identified active services on port 80 (web server)

_**🕒 Key Findings**_
- Firewalls may block ICMP but still respond via ARP
- Intense scans generate significantly more detectable traffic
- Open ports reveal active services (e.g., HTTP on port 80)
- Packet capture tools provide deep visibility into network behavior
- Manual probing demonstrates how attackers identify vulnerabilities

_**⚠️ Security Insights**_
- Excessive scanning activity can trigger IDS/alerts
- Open ports increase attack surface
- ARP and ICMP traffic can reveal internal network structure
- SYN flood attacks can exhaust system resources (DoS risk)

_**🧠 Skills Demonstrated**_
- Network traffic analysis
- Security monitoring & detection
- Vulnerability identification
- Packet inspection and filtering
- Understanding of network protocols (TCP/IP, ARP, ICMP)

