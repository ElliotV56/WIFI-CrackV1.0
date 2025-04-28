# WIFI-CrackV1.0
# WiFi Cracking Tool 🔓📡  
*A powerful security auditing tool for testing Wi-Fi network vulnerabilities (WEP/WPA/WPA2).*  

![GitHub license](https://img.shields.io/github/license/your-username/wifi-crack-tool?color=red)  
![Python](https://img.shields.io/badge/Python-3.x-blue)  

⚠ **Warning**: Use this tool **only** on networks you own or have permission to test. Unauthorized access is illegal.  

---

## Features  
- 🎯 **Multiple Attack Modes**: WEP, WPA-PSK, WPA2-PSK handshake capture.  
- 📡 **Deauthentication Attacks**: Force devices to reconnect for handshake capture.  
- 🔠 **Wordlist Support**: Compatible with RockYou, custom dictionaries.  
- 📊 **Automated Scanning**: Detect nearby networks and weak targets.  
- 🛠 **Offline Cracking**: Save handshakes for later analysis.  

---

## Installation  
### Prerequisites  
- Linux (Kali Linux recommended)  
- Python 3.x  
- `aircrack-ng`, `scapy`, `reaver` (Install via `apt`):  

```bash
sudo apt update && sudo apt install aircrack-ng scapy reaver -y
