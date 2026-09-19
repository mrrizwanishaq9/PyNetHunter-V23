# PyNetHunter V23 🐉

**PyNetHunter V23** is a lightweight, Python-based cybersecurity learning dashboard designed for **Windows and Linux**. It provides a simple terminal interface for exploring system information, network details, security utilities, tool availability, file integrity, Python environment information, and cybersecurity learning topics.

> **Note:** PyNetHunter V23 is an educational Python project inspired by cybersecurity learning environments. It is **not the official Kali NetHunter project**.

---

## 🚀 Features

### 🖥️ System Information

View useful information about your computer:

* Operating system
* OS version
* CPU/processor information
* System architecture
* Python version
* Current username
* Hostname
* Disk storage
* Used and available storage

### 🌐 Network Information

Check basic local network information:

* Hostname
* Local IP address
* Platform information
* Basic network status

### 📡 Internet Connection Test

Quickly test whether the computer can establish an Internet connection.

### 🔧 Cybersecurity Tool Checker

Check whether commonly used cybersecurity-related command-line tools are available on the system.

Supported checks include:

* Nmap
* Wireshark
* SQLMap
* Gobuster
* John the Ripper
* Git
* Python

The program only checks availability; it does not automatically install these tools.

### 📚 Tool Information

Learn the basic purpose of selected security tools, including:

* Nmap
* Wireshark
* SQLMap
* Gobuster
* John the Ripper

### 🔐 SHA-256 Text Hashing

Convert text into a SHA-256 cryptographic hash using Python's built-in `hashlib` module.

### 📁 File Integrity Checker

Calculate the SHA-256 hash of a local file. This can be useful for learning about file integrity and comparing file hashes.

### 🐍 Python Environment

Display information about the Python installation currently running the project:

* Python version
* Python executable path
* Platform information

### 📖 Cybersecurity Learning Center

Includes beginner-friendly learning topics such as:

* Linux fundamentals
* Python programming
* Networking basics
* Cybersecurity fundamentals
* Cryptography basics
* Web security concepts
* Digital security
* CTF and authorized lab practice

### 📝 Activity History

Records the options selected during the current program session so users can review their activity.

---

## 💻 Requirements

* Python **3.10 or newer**
* Windows or Linux
* VS Code recommended
* No external Python packages required

The project mainly uses Python's built-in standard library.

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/PyNetHunter-V23.git
```

Enter the project directory:

```bash
cd PyNetHunter-V23
```

Run the application:

```bash
python PyNetHunter_23.py
```

### Windows with Python 3.13

```powershell
py -3.13 PyNetHunter_23.py
```

---

## 🖥️ Main Menu

The application provides a menu similar to:

```text
====================================================

                 PyNetHunter V23

             CYBERSECURITY LEARNING LAB

====================================================

SYSTEM STATUS

 OS       : Windows
 Python   : 3.13.x
 Host     : YOUR-PC

MAIN MENU

 1. System Information
 2. Network Information
 3. Internet Connection Test
 4. Tool Availability Checker
 5. Tool Information
 6. SHA-256 Text Hash
 7. File SHA-256 Check
 8. Python Environment
 9. Learning Center
10. Activity History
11. About
 0. Exit

PyNetHunter >
```

---

## 🛠️ Technologies Used

* Python 3
* `os`
* `sys`
* `socket`
* `platform`
* `shutil`
* `hashlib`
* `subprocess`
* `datetime`
* `getpass`

No external framework is required for the core project.

---

## 🎯 Learning Objectives

This project can help beginners practice:

* Python functions
* Conditional statements
* Loops
* Dictionaries and lists
* Exception handling
* File handling
* Hashing
* Operating-system interaction
* Network basics
* Command availability detection
* Building terminal-based applications
* Organizing a larger Python project

---

## 🔒 Security & Responsible Use

PyNetHunter V23 is intended for **education, personal systems, CTFs, and authorized security laboratories**.

Only test systems, networks, files, and applications that you own or have explicit permission to test.

Do not use cybersecurity tools against unauthorized systems.

---

## 📂 Project Structure

The basic project can remain extremely simple:

```text
PyNetHunter-V23/
│
├── PyNetHunter_23.py
└── README.md
```

The main application is contained in a single Python file, making it easy for beginners to understand, modify, and run.

---

## 🔮 Future Improvements

Possible future versions could add:

* Graphical user interface
* Dark terminal-style dashboard
* Better Linux/Android compatibility
* Configurable tool database
* Exportable reports
* Log files
* System resource monitoring
* More cybersecurity learning modules
* CTF practice utilities
* Custom themes
* Configuration settings

---

## ⚠️ Disclaimer

PyNetHunter V23 is an independent educational project and is **not affiliated with, sponsored by, or endorsed by Kali Linux or Offensive Security**.

Use all security-related functionality responsibly and only in authorized environments.

---

## ⭐ Project Goal

The goal of PyNetHunter V23 is to give Python learners a practical project where they can combine **Python programming, Linux concepts, networking, system information, cryptography basics, and cybersecurity education** into one simple application.

**Learn Python. Explore Linux. Understand Cybersecurity.**
