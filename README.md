# ⚡ WIFI HACKER ⚡
Developed by: Saad

A professional-grade wireless security auditing tool featuring a custom Python/Tkinter GUI, synchronized hardware-check engine, and a strictly enforced GitHub Dark aesthetic. Now fully optimized as a Standalone Executable (.exe).

## 🚀 Features
GitHub Dark UI: High-contrast aesthetic with #0d1117 background and color-coded signal indicators.

Zero-Dependency: Runs on Windows 10/11 without requiring a Python installation or external libraries.

Enhanced Scan Engine: Real-time SSID discovery with automated protocol detection (WPA2-PSK / WPA3-SAE).

Smart Delay Logic: User-definable attempt delays to maintain hardware synchronization and prevent missed keys.

Session Persistence: Automatically saves progress to .progress.log, allowing you to resume interrupted audits.

One-Click Recovery: Integrated "Copy Password" feature and automated logging to cracked.txt.

## 💻 Requirements
OS: Windows 10 or later.

Privileges: Administrative Privileges (Required to interface with wireless hardware).

Hardware: A compatible internal or USB WiFi adapter.

Wordlist: A standard .txt wordlist (e.g., rockyou.txt or the included probable.txt).

## 🛠️ Installation & Setup
Download WiFi Hacker.exe from the latest release.

Place your wordlist in the same directory as the executable.

No Python or Pip needed! All dependencies are bundled within the binary.

## 🕹️ Usage
Launch: Right-click WiFi Hacker.exe and select "Run as Administrator".

Scan: Click "SCAN NETWORKS" to populate the target list.

Target: Select your target SSID from the table. Note the color-coded strength (Green = Excellent, Yellow = Average, Red = Poor).

Configure: * Verify the Wordlist Path.

Set the Attempt Delay (Default is 5.0s for maximum hardware stability).

Execute: Click "START ATTACK". You can monitor the ETR (Estimated Time Remaining) and current injection status in real-time.

Success: Once compromised, use the "COPY PASSWORD" button. The key is also permanently stored in cracked.txt.

## 📝 Technical Notes
Signal Integrity: Ensure a strong signal for the target. Low signal can cause the hardware to fail a connection attempt even with the correct password.

Anti-Virus: As a security auditing tool, Windows Defender may flag the executable. You may need to add an exclusion or select "Run Anyway" on the Windows SmartScreen popup.

Admin Mode: The "Scan" and "Attack" functions will fail silently if the program is not launched with Administrative rights.

## ⚠️ Disclaimer
This project is created strictly for educational and ethical security testing purposes only. Do NOT use this tool on networks that you do not own or have explicit written permission to test. The author assumes no responsibility for any misuse or damage caused by this software.
