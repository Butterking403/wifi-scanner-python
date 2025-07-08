# wifi-scanner-python
A Python script to scan nearby Wi-Fi networks and show SSID, BSSID, signal strength, and estimated range.
# 🔍 Cross-Platform Wi-Fi Scanner in Python

This is a Python script that scans nearby Wi-Fi networks and displays:

- 📡 **SSID** (Wi-Fi network name)
- 🔐 **BSSID** (MAC address)
- 📶 **Signal strength** in percentage
- 📏 **Estimated range** (Very Close, Medium, Far)

---

## 💻 Works On:
- ✅ Windows (using `netsh`)
- ✅ Linux (using `nmcli` command)

---

## 📦 Requirements

- Python 3.x
- No external libraries needed!
- On Linux: `nmcli` must be installed (usually by default)

---

## 🚀 How to Run

### On Windows:

```bash
python wifi_scanner.py

