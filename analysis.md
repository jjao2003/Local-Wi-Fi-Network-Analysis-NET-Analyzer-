# Network Analysis – Findings & Discussion

This document presents the observations, analysis, and key findings from the Wi-Fi scan performed using the NET Analyzer app.

---

# 1. Router & Network Configuration

### Key Observations
- The Wi-Fi network operates on **Operating Channel: 52**.
- The router uses **WPA2/WPA3** security.
- Frequency band detected: **2.4 GHz / 5 GHz**.
- BSSID indicates a standard home/office access point.
- Gateway IP address and MAC address match expected DHCP/router values.

### Impact
- Proper security (WPA2/WPA3) ensures encrypted traffic.
- 2.4 GHz band shows higher interference in crowded environments.
- Channel selection has a direct influence on performance.

---

# 2. Performance Metrics

### Speed Test Results
- Download speed: **24.7)** Mbps  
- Upload speed: **29.0** Mbps  
- Latency: **8** ms (Idle)
- Jitter: **1)** ms

### Interpretation
- Latency is acceptable for normal browsing and streaming.
- Jitter values indicate occasional signal variation but remain within normal limits.
- Speed is influenced by signal strength and channel congestion.

---

# 3. Signal Strength Across Locations

### Location A (near router)
- Strong signal: around **(e.g., -40 dBm)**
- Highest speed and lowest latency
- Minimal packet loss

### Location B (In the Kitchen)
- Moderate signal: **(e.g., -60 dBm)**
- Slightly reduced speed
- Latency slightly increased

### Location C (In the Corridor)
- Weak signal: **(e.g., -75 dBm or worse)**
- Speed and stability reduced significantly
- Interference becomes more noticeable

### Interpretation
- Physical barriers (walls, doors), distance, and router placement affect performance.
- 2.4 GHz generally penetrates walls better but is more congested.
- 5 GHz offers higher speed but shorter range.

---

# 4. Nearby Networks & Channel Usage

### Findings
- Multiple networks detected on the same or overlapping channels.
- Channels **1, 6, and 11** on 2.4 GHz are heavily used.
- Some networks have strong RSSI values, causing interference.
- Overlapping channels → reduced throughput and higher latency.

### Impact
- Channel congestion leads to:
  - Slower browsing
  - Higher latency
  - More interference
  - Packet loss during peak hours

---

# 5. Overall Network Health

### Strengths
- Security configuration is strong.
- Router is functioning properly.
- Good performance when close to access point.

### Issues Identified
- Channel congestion in the 2.4 GHz band.
- Weak signal in certain rooms.
- Potential suboptimal router placement.
- Interference from multiple networks on the same channel.

---

# 6. Summary
The data shows that the Wi-Fi network performs well under strong signal conditions but suffers when distance and interference increase.  
Channel congestion and weak coverage in some areas are the main issues, requiring optimization.

---
