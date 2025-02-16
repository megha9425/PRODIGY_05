# PRODIGY_05
Develop a packet sniffer tool that captures and analyzes network packets
Packet Sniffer using Scapy: A Python script utilizing Scapy to capture and analyze network packets. It identifies IP, TCP, and UDP packets, extracting and decoding payloads when available. The script prints source/destination IPs, protocol, and decoded payloads for TCP/UDP traffic. Ideal for network analysis and monitoring markdown Copy code

This Python script uses the Scapy library to capture and analyze network packets. It provides basic information about IP, TCP, and UDP packets by extracting and printing details such as source and destination IP addresses, protocol type, and decoded payloads. This tool is useful for network traffic analysis and monitoring.

Features
IP Layer Extraction: Identifies packets with an IP layer and extracts source and destination IP addresses.
Protocol Detection: Determines whether the packet is using TCP or UDP.
Payload Decoding: Attempts to decode and display the payload of TCP and UDP packets in UTF-8 format.
