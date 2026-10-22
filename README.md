 <div align="center">

<img src="./banner_cyberpunk_victor_portscan.png" width="100%" alt="VICTOR PORTSCAN Banner">

# VICTOR PORTSCAN

### Fast & Powerful TCP Port Scanner

**A Python-based TCP port scanner built for speed, simplicity, and network analysis**

<p>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

**Developed by VICTOR**

[Developer](https://github.com/vrntv177) • [Source Code](https://github.com/vrntv177/Portscan)

</div>

---

## 📌 Overview

**VICTOR PORTSCAN** is a Python-based TCP port scanning tool designed for network diagnostics, connectivity testing, and authorized security assessments

The project combines multithreaded scanning, configurable parameters, and a custom terminal interface to provide a straightforward network analysis experience

### Key Highlights

- Fast TCP port scanning
- Open port detection
- IP address and hostname support
- Multithreaded execution
- Customizable connection timeouts
- Scan result export
- Top 10K port scanning mode
- Custom ASCII terminal banner
- Windows PowerShell compatibility

---

## ✨ Features

| Feature | Description |
|:---|:---|
| TCP Scanning | Detect open TCP ports on a target |
| Multithreading | Scan multiple ports concurrently |
| Custom Timeout | Adjust connection timeout settings |
| Top 10K Mode | Scan a larger set of commonly used ports |
| Result Export | Save scanning results to a file |
| Custom Interface | Personalized ASCII art and terminal output |
| CLI Support | Run scans directly from the command line |

---

## 📦 Installation

### Requirements

- Python 3.x
- Windows PowerShell or a compatible terminal
- Git (optional, for cloning the repository)

### Step 1 — Clone the repository

```bash
git clone https://github.com/vrntv177/Portscan.git
```

### Step 2 — Navigate to the project

```bash
cd Portscan
```

### Step 3 — Install dependencies

If your version requires `pythonping`, install it using:

```bash
py -m pip install pythonping
```

---

## 🚀 Usage

### Basic Scan

```bash
py portscan_victor.py -t 127.0.0.1
```

### Scan Top 10K Ports

```bash
py portscan_victor.py -t 127.0.0.1 --top-10k
```

### Custom Timeout

Set a connection timeout of 240 milliseconds:

```bash
py portscan_victor.py -t 127.0.0.1 --timeout 240
```

### Custom Thread Count

```bash
py portscan_victor.py -t 127.0.0.1 --threads 50
```

### Export Scan Results

```bash
py portscan_victor.py -t 127.0.0.1 -o results.txt
```

### Display Help

```bash
py portscan_victor.py --help
```

---

## ⚙️ Command-Line Arguments

| Argument | Description |
|:---|:---|
| `-t, --target` | Target IP address or hostname |
| `--timeout` | Connection timeout in milliseconds |
| `--threads` | Number of concurrent scanning threads |
| `-o, --output` | Save results to an output file |
| `--top-10k` | Enable Top 10K port scanning |
| `-h, --help` | Display available commands |

---

## 📊 Example Output

```text
[ PINGING ON DOMAIN... ]

Domain  = 127.0.0.1
Timeout = 240 ms
Threads = 30

[ RESULTS ]

[+] 80    -> Open
[+] 443   -> Open
[+] 8080  -> Open

[#] 3 Open ports
[i] Scan completed
```

> This is an illustrative example. Actual results depend on the target and its available services

---

## 🗂️ Project Structure

```text
Portscan/
│
├── portscan_victor.py
├── banner_cyberpunk_victor_portscan.png
├── LICENSE
└── README.md
```

---

## 🛠️ Technologies

| Technology | Purpose |
|:---|:---|
| Python | Core development |
| Sockets | TCP network connections |
| Threading | Concurrent execution |
| Argparse | Command-line argument handling |
| ANSI / ASCII | Terminal interface customization |

---

## 🎯 Project Goals

VICTOR PORTSCAN was developed to explore and improve practical knowledge in:

- Python programming
- TCP/IP networking
- Socket communication
- Multithreaded applications
- Network diagnostics
- Command-line tool development

---

## 🔮 Roadmap

Potential improvements for future releases:

- [ ] Service detection
- [ ] JSON and CSV export
- [ ] Real-time progress bar
- [ ] Interactive terminal interface
- [ ] Advanced scanning reports
- [ ] Performance optimization
- [ ] Cross-platform improvements

---

## 🔐 Security & Responsible Usage

**VICTOR PORTSCAN is intended for educational purposes, network diagnostics, and authorized security assessments only**

Use this software exclusively on systems you own or have explicit permission to test

An open port does not necessarily indicate a security vulnerability

Users are responsible for complying with applicable laws and obtaining proper authorization before performing network scans

---

## 📜 License

This project is distributed under the **MIT License**, to the extent that the project owner holds the necessary licensing rights

See the [LICENSE](LICENSE) file for more information

The MIT License requires preservation of the copyright and permission notices in copies or substantial portions of the licensed software

---

## 👨‍💻 Developer

<div align="center">

### VICTOR

**Python Developer | Networking & Cybersecurity Enthusiast**

[![GitHub](https://img.shields.io/badge/GitHub-vrntv177-181717?style=for-the-badge&logo=github)](https://github.com/vrntv177)

---

### VICTOR PORTSCAN

**FAST • POWERFUL • CUSTOMIZABLE**

Made with Python

Copyright © 2026 VICTOR

</div>
