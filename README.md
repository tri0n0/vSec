# 🔐 vSecure IDS — Real-time Intrusion Detection System with Snort + Python GUI

![Snort](https://img.shields.io/badge/Snort-Powered-ff69b4?logo=snort&style=for-the-badge)
![Python](https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge&logo=checkmarx)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

🌟 **A lightweight, real-time Intrusion Detection System (IDS)** tailored for small-to-medium networks and educational use, blending **Snort's deep packet inspection** with a **Python-powered GUI** for ease of use and instant threat visibility.

---

## 🚀 Key Features

- ⚡ **Real-Time Threat Detection** using custom Snort rules
- 🔍 **Detection of Nmap-based scans**: SYN, NULL, FIN, XMAS, OS Fingerprinting, ICMP Ping
- 🧠 **Anomaly + Signature-based Detection** architecture
- 📉 **Low False Positive Rate** with rule tuning and test cases
- 💻 **User-Friendly Python GUI** (built with Tkinter) to Start/Stop, visualize, and log detections
- 💠 Runs in **WSL/Linux** with support for **cross-network testing**
- 🏆 **Featured at IBM Technovate 2025** 🎉

---

## 🖼️ Preview

> _(Insert your own GIFs here, here's what you can record or use)_

| Feature | Preview |
|--------|---------|
| 🧪 Scanning & Detection | ![Screenshot 2025-05-21 193321](https://github.com/user-attachments/assets/7c488048-0857-4baf-b57e-3eb8bd7f3ffd)
 |
| 💾 GUI Interface | ![Screenshot 2025-05-21 193147](https://github.com/user-attachments/assets/94900325-64f1-481e-b9c7-78b1108eab95)
media/xT0xeJpnrWC4XWblEk/giphy.gif) |

---

## 🛠️ Tech Stack

| Component        | Description |
|------------------|-------------|
| **Snort**        | Core detection engine (rule-based) |
| **Python (Tkinter)** | GUI for simplified IDS management |
| **Nmap**         | Simulated attack tool for scan-based tests |
| **LibDAQ + CMake** | Dependencies for Snort |
| **Linux (WSL)**  | Development environment |

---

## ⚙️ How It Works

1. 🔄 **Snort listens** to network packets via selected interfaces
2. 📌 Custom rules match patterns like Nmap scans and ping attempts
3. 🔔 Alerts are generated and saved in real-time logs (`alert_fast.txt`)
4. 👡 Users control monitoring via GUI — no CLI needed!

---

## 📈 Achievements

🏋️ Selected as a **Top Project at IBM Technovate 2025**, recognized by IBM professionals for its **usability, innovation, and real-world relevance**.

---

## 🧪 Test Coverage

> Includes 7+ detailed test cases:
- ✅ Detection of OS fingerprinting and various Nmap scans
- ✅ Cross-network scanning simulation
- ✅ False positive mitigation

---

## 📚 References

- [Snort Official Docs](https://www.snort.org/documents)
- [Nmap Command Guide](https://nmap.org/book/man.html)
- [Tkinter GUI Guide](https://www.geeksforgeeks.org/python-tkinter-tutorial/)

---

## 🧑‍💻 Authors

👤 Chinmoy Das  
👤 Abhishek Dutta

> Guided by **Dr. Mala Dutta**, Associate Professor, Assam down town University

---

## 🔮 Future Scope

- Integration with **machine learning** models for zero-day detection  
- Web dashboard using **Flask or Django**  
- Integration with **threat intelligence APIs**

---
