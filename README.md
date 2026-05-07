# Login-Anomaly-Detector---Advanced-Multi-Language-Ethical-Hacking-Security-Tool
🔒 Advanced login anomaly detection system built for Termux with Python, Node.js,  Lua &amp; Go. Detects brute force attacks, impossible travel, unusual times, and  suspicious patterns. Perfect for bug bounty hunters and security researchers.
# 🔐 Login Anomaly Detector

**Advanced Multi-Language Ethical Hacking Security Tool for Termux**

[

![Python](https://img.shields.io/badge/Python-3.x-blue)

](https://www.python.org/)
[

![Node.js](https://img.shields.io/badge/Node.js-14+-green)

](https://nodejs.org/)
[

![Lua](https://img.shields.io/badge/Lua-5.x-purple)

](https://www.lua.org/)
[

![Go](https://img.shields.io/badge/Go-1.16+-orange)

](https://golang.org/)
[

![License](https://img.shields.io/badge/License-MIT-yellow)

](#license)
[

![Platform](https://img.shields.io/badge/Platform-Termux%2FAndroid-red)

](https://termux.com/)

A comprehensive login anomaly detection system designed for security professionals, 
ethical hackers, and penetration testers. Built with a multi-language architecture 
combining Python 3, JavaScript/Node.js, Lua, and Go for maximum flexibility and performance.

## 🚀 Features

### Core Detection Capabilities
- ✅ **Brute Force Detection** - Identifies multiple failed login attempts (5+ in 5 minutes)
- ✅ **Geographic Anomalies** - Detects impossible travel patterns
- ✅ **Temporal Patterns** - Finds unusual login times and deviations
- ✅ **Device Fingerprinting** - Tracks logins from new/unknown devices
- ✅ **Behavioral Analysis** - Identifies deviations from baseline patterns
- ✅ **Velocity Checks** - Detects rapid successive logins

### Advanced Features
- 🎨 **Real-Time Dashboard** - Live monitoring with statistics updates
- 📊 **Data Visualization** - Charts and graphs of login patterns
- 📈 **Pattern Analysis** - Statistical anomaly detection algorithms
- 🌐 **Network Analysis** - IP reputation and risk scoring
- 💾 **Multi-Format Export** - JSON, CSV export capabilities
- 📝 **Comprehensive Logging** - Detailed audit trails
- ⚙️ **Configurable Thresholds** - Customize detection sensitivity

### Multi-Language Architecture
- 🐍 **Python 3** - Core detection engine with advanced algorithms
- 📦 **Node.js** - Real-time dashboard and data visualization
- 🌙 **Lua** - Lightweight fast pattern matching analyzer
- ⚡ **Go** - High-performance network and IP analysis
- 🔧 **Bash** - System integration and automation

## 📋 Requirements

- **Termux** (latest version)
- **Android 7.0+** (recommended 9.0+)
- **50MB free storage**
- **Internet connection** (for installation)

## ⚡ Quick Installation

### Automated Setup (Recommended)

```bash
# One-line installation
apt update && apt install -y python3 pip sqlite nodejs lua golang && \
pip install --upgrade pip && pip install sqlite3 && \
npm install -g chalk sqlite3 && \
mkdir -p ~/.anomaly_detector && chmod 700 ~/.anomaly_detector
# Clone the repository
git clone https://github.com/yourusername/login-anomaly-detector.git
cd login-anomaly-detector

# Install dependencies
bash install.sh

# Test installation
bash test_suite.sh

# Initialize database
python3 login_anomaly_detector.py --baseline

#Interactive mode easiest way
python3 login_anomaly_detector.py
