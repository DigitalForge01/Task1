# Task1
1.Installed Nmap (with Npcap) on Windows
Ensured that the nmap command works along with raw packet support needed for TCP SYN scans.

2.Determined your local IPv4 network block
From 10.174.146.34 / 255.255.255.0 → derived the network 10.174.146.0/24.

3.Ran a TCP SYN scan on the subnet
Detecting live hosts, open TCP ports.

4.Captured packet-level traffic with Wireshark (optional)
Used tcp and (syn or rst) filter to isolate scan traffic in a .pcap.

5.Interpreted open ports and common services
Focused on ports 135, 139, 445, 3306, mapping them to Microsoft RPC, SMB, NetBIOS, and MySQL services.

6.Assessed security risk for those exposed ports
Ranked each port/service by risk level (e.g., SMB EternalBlue, open MySQL brute-force), and noted the need for patching, restriction, or removal.
