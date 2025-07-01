# Network-captures
Capturing live network packets and identifying basic protocols and traffic types.
Network Traffic Analysis with Wireshark

This project documents the steps carried out to capture and analyze network traffic using **Wireshark**, a powerful open-source packet analyzer.

Objective:-

Capture real-time network traffic, filter by protocol, identify at least 3 protocols, and export the traffic to a .pcap file. Finally, summarize observations and findings.

Tools Used

Wireshark– GUI-based network packet analyzer
Web browser– To generate HTTP/HTTPS traffic
Command-line tool– For ping requests (ping google.com)

Steps Performed

1. Install Wireshark
- Downloaded from the official website: [https://www.wireshark.org/](https://www.wireshark.org/)
- Installed with default settings and included (Npcap) for packet capture support

2. Launched Wireshark
- Opened Wireshark with administrative privileges
- Identified active network interface (Wi-Fi in this case) by monitoring packet activity

3. Started Packet Capture
- Double-clicked on the Wi-Fi interface to begin capturing live traffic

4. Generated Network Traffic
- Browsed websites like example.com, openai.com
- Ran command: ping google.com to generate ICMP packets

5. Stopped Capture
- Waited ~60 seconds to collect a meaningful amount of traffic
- Clicked the red square stop button in Wireshark to end the capture

6. Filtered by Protocol
Used Wireshark’s filter bar to inspect specific protocols:

plaintext:
dns
tcp
icmp
http
tls



Packet Capture Summary:-

Interface: Wi-Fi
Duration: 1 minute
Traffic Generated: Website browsing and ping to google.com

Protocols Observed:
DNS – Domain name resolution (e.g., google.com → IP)

TCP – Transport protocol used by HTTP/TLS

TLS – Encrypted communication for HTTPS websites


.pcap File Exported: network-capture.pcap
alongwith all screenshots of steps performed.
