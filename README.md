# Wireshark-Network-Traffic-Capture
Capture and Analyze Network Traffic Using Wireshark
# Objective
Capture live network packets using Wireshark and identify basic protocols and traffic types. This task helps in gaining hands-on packet analysis skills and protocol awareness.
Tools Used
Wireshark (free network protocol analyzer)
# Steps Followed
Installed Wireshark from the official website (wireshark.org).
Started capturing on the active network interface (Wi-Fi in my case).
Generated traffic by browsing a website (e.g., google.com) and pinging a server (e.g., ping google.com).
Stopped the capture after about 1 minute.
Filtered captured packets by protocols such as HTTP, DNS, and TCP.
Identified at least 3 different protocols in the capture: TCP (for reliable connections), HTTP (for web traffic), and DNS (for domain name resolution). Also saw others like ICMP from pings.
Exported the capture as a .pcap file named network_capture.pcap.
Summarized findings in this README and a separate report file.
Findings and Packet Details
Total Packets Captured: Approximately 2,400 (as seen in the capture).
Protocols Identified:
TCP: Used for establishing connections, e.g., source port 18974, destination port 80, with ACK and SEQ numbers.
HTTP: Web requests, e.g., GET requests to servers.
DNS: Queries for domain resolution, if browsing was done.
Other: ICMP (from pings), possibly UDP if any was generated.
Example Packet Detail: A TCP packet from source IP (local) to destination (e.g., 8.8.8.8 for Google DNS), length 80 bytes, with flags like ACK.
The capture showed typical internet traffic, including handshakes and data transfers. Filtering helped isolate specific protocols for analysis.
Packet capture helps in troubleshooting network issues by revealing errors, delays, or unauthorized traffic.
# What I Learned
Wireshark is a powerful tool for monitoring network traffic in real-time.
Packets are the basic units of data transmitted over networks, containing headers and payloads.
Differences between protocols: TCP is connection-oriented and reliable, UDP is faster but unreliable.
Filtering (e.g., "http" or "dns") makes analysis easier.
This exercise improved my understanding of TCP/IP, network troubleshooting, and protocol analysis.
# Key Concepts: Packet capture, protocol analysis, TCP/IP, network troubleshooting, filtering.
