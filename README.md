# DroidCOP

Advanced Android Forensics & Threat Detection Tool

DroidCOP is an Android device inspection and forensic analysis tool that detects suspicious behavior, malware indicators, dangerous permissions, and system anomalies on connected Android devices.

Designed for security researchers, penetration testers, and digital forensic analysts.

---

## Download

[Download DroidCOP.exe](YOUR_DRIVE_LINK_HERE)

Standalone Windows executable — No Python installation required.

---

## Features

DroidCOP performs deep Android device security inspection using ADB-based analysis and behavioral heuristics.

### Device Security Checks

- Suspicious APK detection
- Hidden APK discovery
- Malware package detection
- Dangerous permission audit
- Background service inspection
- Clipboard monitoring app detection
- Camera and microphone usage analysis
- Foreground service abuse detection

### Advanced Threat Analysis

- Known spyware package detection
- Accessibility service abuse detection
- SELinux violation detection
- Logcat anomaly scanning
- Battery drain analysis
- Suspicious system service inspection
- Malware behavioral indicators

---

## Risk Scoring System

DroidCOP calculates a device risk score based on detected indicators.

Severity Levels:

LOW – Minor suspicious indicators  
MEDIUM – Potentially unsafe configuration  
HIGH – Strong suspicious activity  
CRITICAL – Likely malware or spyware behavior  

The final report includes a clear severity rating and investigation details.

---

## Usage

DroidCOP runs from the command line.

Basic scan:

```
DroidCOP.exe --scan
```

Deep scan:

```
DroidCOP.exe --deep
```

Scan specific device:

```
DroidCOP.exe --device <device_id>
```

Export report:

```
DroidCOP.exe --report report.txt
```

---

## Example Output

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

## Generated Report

DroidCOP generates a clean forensic text report including:

- Device information
- Installed apps analysis
- Suspicious permissions
- Malware indicators
- Behavioral anomalies
- Final risk score

Example:

```
Device Risk Score : 72
Severity : HIGH

Findings:

• Suspicious foreground service detected
• Hidden APK discovered
• Clipboard monitoring app detected
• Known spyware package detected
```

---

## Requirements

- Windows OS
- ADB installed and accessible in PATH
- Android device with USB debugging enabled

Verify ADB connection:

```
adb devices
```

---

## Use Cases

- Android malware investigation
- Digital forensic analysis
- Security research
- Corporate device security auditing
- Pentesting labs
- Spyware detection
- Suspicious device inspection

---

## Disclaimer

This tool is intended only for educational, research, and authorized security testing purposes.

Unauthorized scanning of devices without permission may be illegal.

The developer is not responsible for misuse of this tool.

---

## Author

Akshar Ratnani

Security Researcher  
Android Pentesting  
Offensive Security

---

## Support

If you find this project useful:

⭐ Star the repository  
🍴 Fork the project  
🛠 Contribute improvements
