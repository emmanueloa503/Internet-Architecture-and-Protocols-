# Internet-Architecture-and-Protocols-
This labs focus on analyzing how real networks behave using tools like tcpdump, Wireshark, routing tables, ARP, and iperf3 throughput measurements.

🔍 Key Concepts Demonstrated

ARP (Address Resolution Protocol):
Captured and analyzed ARP requests/replies to observe MAC↔IP resolution and validate host connectivity.

Ethernet & Switching Behavior:
Verified MAC learning, switching tables, and frame forwarding across bridges and LAN segments.

ICMP & Ping Diagnostics:
Inspected ICMP echo request/reply packets to understand IP-level reachability and network delays.

Subnetting & IP Addressing:
Designed subnets for multiple LANs, calculated network/broadcast ranges, and configured routers/hosts accordingly.

Routing Configuration:
Set static routes on routers and hosts to enable full connectivity across three LANs using longest prefix matching.

Throughput Testing (iperf3):
Measured link performance between hosts under different L2/L3 paths to understand bandwidth, latency, and bottlenecks.

Firewall Rules (iptables):
Implemented DROP and REJECT rules to block Telnet traffic and validated behavior using packet captures.

SFTP/SSH Traffic Analysis:
Used Wireshark to decode TCP streams and identify encrypted SSH handshake patterns and port behavior.
