# WIFI-CrackV1.0
# WiFi Cracking Tool 🔓📡  
*A powerful security auditing tool for testing Wi-Fi network vulnerabilities (WEP/WPA/WPA2).*  

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Termux](https://img.shields.io/badge/Termux-000000?style=for-the-badge&logo=termux&logoColor=white)
![Parrot OS](https://img.shields.io/badge/Parrot_OS-FF6600?style=for-the-badge&logo=parrotos&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
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

## 📸 Screenshots  

### **SCREENSHOTS**  
![WCRACK](main.png)  

### **SCREENSHOTS**  
![WCRACK](main2.png)  


## Installation  
Tested On :

    Kali Linux
    BlackArch Linux
    Ubuntu
    Kali Nethunter
    Termux ( Rooted Devices)
    Parrot OS

### Prerequisites  
- 𝙆𝘼𝙇𝙄 ![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
- 𝐓𝐄𝐑𝐌𝐔𝐗 ![Termux](https://img.shields.io/badge/Termux-000000?style=for-the-badge&logo=termux&logoColor=white)
-  𝐏𝐚𝐫𝐫𝐨𝐭 𝐎𝐒 ![Parrot OS](https://img.shields.io/badge/Parrot_OS-FF6600?style=for-the-badge&logo=parrotos&logoColor=white)
-  𝐔𝐛𝐮𝐧𝐭𝐮 ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

# WiFi Toolkit for Ubuntu ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

```bash
# 1. Update system
sudo apt update && sudo apt full-upgrade -y

# 2. Install critical tools
sudo apt install -y \
    git \
    aircrack-ng \
    python3-pip \
    libssl-dev \
    wireless-tools \
    hcxdumptool

# 3. Clone repository
git clone https://github.com/Ell


# WiFi Toolkit for Parrot OS ![Parrot OS](https://img.shields.io/badge/Parrot_Security-FF6600?style=for-the-badge&logo=parrotsecurity&logoColor=white)

```bash
# 1. Update system (Parrot uses special upgrade)
sudo apt update && sudo parrot-upgrade -y

# 2. Install missing dependencies (most tools pre-installed)
sudo apt install -y python3-pip hcxtools

# 3. Clone repository
git clone https://github.com/ElliotV56/WIFI-CrackV1.0.git
cd WIFI-CrackV1.0

# 4. Install Python requirements
pip3 install -r requirements.txt

# 5. Run tool (usually needs sudo for packet injection)
sudo python3 WIFI-C.py


# WiFi Auditing Toolkit for Kali Linux ![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)

```bash
# 1. Update Kali (always do this first)
sudo apt update && sudo apt full-upgrade -y

# 2. Install additional tools (most are pre-installed)
sudo apt install -y hcxtools hcxdumptool bully

# 3. Clone the repository
git clone https://github.com/ElliotV56/WIFI-CrackV1.0.git
cd WIFI-CrackV1.0

# 4. Install Python requirements
pip3 install -r requirements.txt

# 5. Put your Wi-Fi card in monitor mode
sudo airmon-ng check kill
sudo airmon-ng start wlan0

# 6. Run the tool with elevated privileges
sudo python3 WIFI-C.py
