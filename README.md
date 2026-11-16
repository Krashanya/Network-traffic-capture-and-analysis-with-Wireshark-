# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

<img width="1078" height="676" alt="image" src="https://github.com/user-attachments/assets/c5f77406-6477-4f69-8526-359c14194971" />

<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/1680b67e-7feb-4ea4-abde-239501663e74" />

<img width="1600" height="779" alt="image" src="https://github.com/user-attachments/assets/4a1036f0-43a5-4f74-b72c-7a4e93e12862" />

<img width="1600" height="740" alt="image" src="https://github.com/user-attachments/assets/74fd597a-0e32-41ba-b0b7-557b0ea0da1c" />





## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
