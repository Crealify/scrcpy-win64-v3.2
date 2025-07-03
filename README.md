# 📱 scrcpy-win64-v3.2

This repository provides a **ready-to-use Windows version** of [scrcpy](https://github.com/Genymobile/scrcpy) — a free and open-source tool to display and control Android devices from your PC via USB or Wi-Fi.

> ✅ No installation required — just extract and run.

---

## 🔧 What is scrcpy?

`scrcpy` allows you to mirror your Android device screen and control it from your desktop using keyboard and mouse. It supports high performance, low latency, and works on **Windows, macOS, and Linux**.

This repository provides:
- Prebuilt `scrcpy` binaries for **Windows 64-bit**
- Required dependencies (DLLs, ADB, server, etc.)
- Easy-to-run `.bat` files and scripts

---

## 🗂️ Included Files

| File | Description |
|------|-------------|
| `scrcpy.exe` | Main executable |
| `adb.exe` | Android Debug Bridge binary |
| `.dll` files | Required dependencies (e.g., SDL2, libusb, ffmpeg components) |
| `scrcpy-console.bat` | Run scrcpy with console output |
| `scrcpy-noconsole.vbs` | Run scrcpy silently (no console window) |
| `open_a_terminal_here.bat` | Opens CMD in current folder |
| `scrcpy-server` | Server binary pushed to Android device |

---

## 🚀 How to Use

### 1. 📦 Download & Extract

Download the ZIP of this repository and extract it anywhere on your PC.

### 2. 📱 Enable USB Debugging

On your Android device:
- Go to **Settings > About phone**
- Tap **Build number** 7 times to enable Developer Options
- Go to **Developer Options** and enable **USB Debugging**

### 3. 🔌 Connect Device

Plug your Android device into your PC via USB.

### 4. ▶️ Run scrcpy

Double-click:
- `scrcpy-console.bat` (with console window), or  
- `scrcpy-noconsole.vbs` (silent launch)

---

## 💡 Notes

- First time use will prompt **"Allow USB debugging"** on your phone. Check **"Always allow"** and tap OK.
- Works wirelessly if ADB over TCP/IP is enabled (`adb tcpip 5555`)

---

## 🖥️ Requirements

- Android device (5.0 or higher)
- USB cable or Wi-Fi ADB setup
- Windows 64-bit system

---

## 📜 License

This package includes binaries built from the [Genymobile/scrcpy](https://github.com/Genymobile/scrcpy) open-source project (licensed under the Apache 2.0 License).  
Refer to their repo for source code and contributions.

---

## 🙌 Credits

- [scrcpy](https://github.com/Genymobile/scrcpy) by **Genymobile**
- Precompiled and shared by [Crealify](https://github.com/Crealify)

---

## 📂 Repository Info

- Version: v3.2
- Status: ✅ Ready to use
- Languages: Batch, VBScript

