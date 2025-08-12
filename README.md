# Elevate Labs Task 5 – Network Traffic Capture & Analysis

## Task Overview
Captured live network packets using Wireshark to identify different protocols and analyze traffic patterns.

## What I Did
- Launched Wireshark with Npcap enabled.
- Selected the active Ethernet interface.
- Captured traffic for ~2 minutes while browsing and pinging.
- Applied filters (`tcp`, `udp`, `tls`) to inspect specific protocols.
- Saved results as `task5_capture.pcap`.

## Key Learning
- TCP is reliable, using handshakes for connection setup.
- UDP is fast and connectionless.
- TLS secures web traffic by encrypting payloads.
- Packet analysis is vital for troubleshooting and security.

## Artifacts
- `task5_capture.pcap`
- `screenshots/` (filtered protocol views)
- `README.md`
