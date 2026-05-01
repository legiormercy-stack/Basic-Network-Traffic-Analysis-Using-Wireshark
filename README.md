# Basic-Network-Traffic-Analysis-Using-Wireshark

## Objective
To analyze network traffic using packet capture techniques in order to identify and understand DNS queries, responses, and general network communication patterns.
By filtering DNS traffic, I was able to observe query requests and responses between a client and DNS server, as well as inspect packet-level details across multiple protocol layers.

### Skills Learned
- Network traffic analysis and packet inspection.
- Packet filtering using Wireshark display filters.
- Identifying source and destination IP addresses.
- Analyzing DNS queries and responses.
- Reading raw packet data.

### Tools Used
- Wireshark for packet capture and analysis.
- Network interface (Wi-Fi) for capturing live traffic.
- Windows OS analysis environment.

## Steps
<img width="1366" height="768" alt="Screenshot (557)" src="https://github.com/user-attachments/assets/b9cf6133-b034-47d4-86fa-4ecb545b4750" />
DNS Traffic Analysis in Wireshark
This screenshot shows filtered DNS traffic within Wireshark. The analysis highlights DNS queries and responses between source IP 10.165.218.248 and destination IP 10.165.218.4
This demonstrates the ability to filter, interpret, and analyze real network traffic at both high and low levels.

##Key Findings 
- Multiple DNS queries were observed for external services like Google APIs and ASUS update servers.
- Traffic followed standard DNS communication over UDP port 53.
- No immediate malicious traffic detected, indicating normal system activity.
