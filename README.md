<h4 align="center"> If you find this GitHub repo useful, please consider giving it a star! ⭐️ </h4> 

<p align="center">
    <a href="https://facebook.com/AriYan.MirZa.Just.For.You">
      <img src="https://img.shields.io/badge/Facebook-AriYan_MirZa-black?logo=facebook&style=for-the-badge">
    </a>
    &nbsp;
    <a href="https://t.me/ariyan_mirza_tm">
      <img src="https://img.shields.io/badge/Telegram-@ariyan__mirza__tm-black?logo=telegram&style=for-the-badge">
    </a>
    &nbsp;
    <a href="https://github.com/ariyanopu">
      <img src="https://img.shields.io/badge/GitHub-ariyanopu-black?logo=github&style=for-the-badge">
    </a>
</p>

<p align="center">
  <img width="20%" src="https://github.com/spyboy-productions/CamXploit/blob/main/CCTV%20recon.jpg" />
</p>

---

## 📷 CamFucker (Modified Version)

**CamFucker** is a reconnaissance-based CCTV research tool designed to help security researchers and cyber enthusiasts identify exposed CCTV cameras on public IP addresses.

It performs:
- Massive port scanning (1000+ ports)
- CCTV login page detection
- Default credential testing
- Live stream detection (RTSP / HTTP / RTMP / MMS)
- Camera brand & DVR/NVR identification
- IP & location intelligence with Google Maps/Earth links

⚠️ **Disclaimer:**  
This tool is strictly for **educational and authorized security testing only**.  
Scanning systems without permission is illegal. The author is not responsible for misuse.

---

## 🚀 Features

✔️ Scan common & custom CCTV ports  
✔️ Detect exposed camera login panels  
✔️ Identify camera brands & DVR/NVR devices  
✔️ Default credential checking  
✔️ Live stream detection & validation  
✔️ Google dorking & OSINT links  
✔️ Multi-threaded scanning for speed  
✔️ ONVIF protocol support  
✔️ IP geolocation with map links  
✔️ Smart brute-force protection  

---

## 📚 Supported Devices

- Hikvision  
- Dahua  
- CP Plus (DVR/NVR)  
- Axis  
- Sony  
- Bosch  
- Samsung  
- Panasonic  
- Vivotek  
- Generic DVR / NVR / IP Cameras  

---

## 🛠️ Installation (Termux / Linux)

### 📱 Termux Commands

```bash
apt update -y
apt upgrade -y
pkg install python -y
pkg install git -y
git clone https://github.com/ariyanopu/CamFucker.git
cd CamFucker
python CamFucker.py
