<p align="center">
  <img src="logo.png" width="420">
</p>

<h1 align="center">DroidCOP</h1>

<p align="center">
Advanced Android Forensics & Threat Detection Tool
</p>

<p align="center">

![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Security%20Tool-red?style=for-the-badge)
![Built With](https://img.shields.io/badge/Built%20With-Python-yellow?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-2.0-green?style=for-the-badge)

</p>

---

# 🔍 Overview

**DroidCOP** is an advanced Android device forensic inspection and threat detection tool that analyzes connected Android devices using **ADB** and detects suspicious behavior, malware indicators, dangerous permissions, and system anomalies.

Designed for:

- 🔐 Security Researchers  
- 🧪 Malware Analysts  
- 🕵️ Digital Forensic Investigators  
- 💻 Android Pentesters  

---

# ⬇️ Download

<p align="center">

<a href="WINDOWS_DOWNLOAD_LINK">
<img src="https://img.shields.io/badge/Download-Windows%20EXE-brightgreen?style=for-the-badge&logo=windows">
</a>

<a href="LINUX_DOWNLOAD_LINK">
<img src="https://img.shields.io/badge/Download-Linux%20BIN-orange?style=for-the-badge&logo=linux">
</a>

</p>

Standalone executables — **No Python installation required**

---

# ✨ Features

## 🧪 Device Inspection

- Suspicious APK detection
- Hidden APK discovery
- Malware package detection
- Dangerous permission audit
- Background service inspection
- Clipboard monitoring app detection
- Camera and microphone usage analysis
- Foreground service abuse detection

---

## 🛡 Advanced Threat Analysis

- Known spyware package detection
- Accessibility service abuse detection
- SELinux violation detection
- Logcat anomaly scanning
- Battery drain analysis
- Suspicious system service inspection
- Malware behavioral indicators

---

# 🧠 Intelligent Risk Scoring

DroidCOP calculates a **device risk score** based on detected indicators.

| Severity | Meaning |
|--------|--------|
| 🟢 LOW | Minor suspicious indicators |
| 🟡 MEDIUM | Potentially unsafe configuration |
| 🟠 HIGH | Strong suspicious activity |
| 🔴 CRITICAL | Likely malware or spyware behavior |

Each detection contributes to the **final device risk score**.

---

# ⚙️ Usage

## Windows

Run the executable:

```
DroidCOP.exe --scan
```

Deep scan:

```
DroidCOP.exe --deep
```

---

## Linux

Make the binary executable:

```
chmod +x DroidCOP.bin
```

Run the tool:

```
./DroidCOP.bin --scan
```

Deep scan:

```
./DroidCOP.bin --deep
```

---

# 📄 Example Output

```
[+] Device Connected
[+] Starting DroidCOP Scan...

[INFO] Checking installed applications
[INFO] Analyzing permissions
[WARNING] Suspicious clipboard access detected
[ALERT] Hidden APK discovered
[ALERT] Known spyware package detected

Device Risk Score : 72
Severity : HIGH
```

---

# 🖥 Requirements

- ADB installed
- Android device with **USB Debugging enabled**

Verify connection:

```
adb devices
```

---

# 📊 DroidCOP Workflow

```
Connect Android Device
        │
Enable USB Debugging
        │
Run DroidCOP
        │
System Inspection
        │
Threat Detection
        │
Risk Scoring
        │
Report Generated
```

---

# 🧰 Use Cases

- Android malware investigation
- Digital forensic analysis
- Corporate device auditing
- Security research labs
- Spyware detection
- Android pentesting

---

# ⚠️ Disclaimer

This tool is intended **only for educational and authorized security testing purposes**.

Do not scan devices without permission.

The developer assumes **no responsibility for misuse**.

---

# 👨‍💻 Author

**Akshar Ratnani**

Security Researcher  
Android Pentesting  
Offensive Security  

---

# ⭐ Support

If you find this project useful:

⭐ Star the repository  
🍴 Fork the project  
🛠 Contribute improvements  
