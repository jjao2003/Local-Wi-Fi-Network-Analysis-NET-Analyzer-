# Wi-Fi Network Measurement Tables

This file contains all raw data collected using NET Analyzer.

---

# 1. Main Network Details

| Parameter | Value |
|----------|-------|
| SSID | *DNA-WIFI-5Ghz-2267* |
| BSSID | *06:e3:1a:e4:22:66* |
| Router IP Address | *192.168.101.101* |
| Device Local IP | *192.168.101.1* |
| MAC Address | *06:e3:1a:e4:22:66* |
| Security Type | WPA2 / WPA3 (AES) |
| Frequency Band | 2.4 GHz / 5 GHz |
| Operating Channel | *52 (5260 MHz)* |
| Channel Width | *80 MHz* |
| Signal Strength (general) | *-44 dBm* |

---

# 2. Performance Measurements

| Metric | Value |
|--------|--------|
| Download Speed | *24.7 Mbps* |
| Upload Speed | *29.0 Mbps* |
| Ping (Latency) | *8 ms (Idle)* |
| Jitter | *1 ms* |

---

# 3. Location-Based Measurements

| Location | Signal Strength (dBm) | Download (Mbps) | Upload (Mbps) | Ping (ms) |
|----------|------------------------|-----------------|----------------|-----------|
| Location A (near router) |-44 dBm |24.7 |29.0 |8 |
| Location B (Kitchen) |-53 dBm |-- |-- |-- |
| Location C (Corridor) |-76 dBm |-- |-- |-- |

---

# 4. Nearby Networks Detected

| SSID | Channel | Signal Strength | Security | Notes |
|------|---------|------------------|----------|--------|
|TP-Link_AEB6 |9 |-32 dBm |WPA2 (AES) |Strongest neighbor; high interference risk. |
|DNA-Mokkula-2G-D8MF58 |3 |-50 dBm |WPA2 (AES) |Overlaps with multiple channels. |
|Home Net |7 |-51 dBm |WPA2 (AES) |Active in Kitchen area. |
|Redmi 9C NFC |6 |-54 dBm |WPA2 (AES) |Mobile hotspot interference in corridor. |
|Nothing Phone (3a) Pro	|10	|-54 dBm	|WPA3/WPA2	|Modern device on non-standard channel. |
---

# 5. Screenshots Reference

All screenshots are stored in the `/screenshots/` folder:

- `network-info.png` – Network details  
- `wifi-scanner.png` – Channel scan  
- `speed-test.png` – Speed test  
- etc.

---
