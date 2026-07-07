# 🔐 File Integrity Monitor (FIM)

A File Integrity Monitor (FIM) is a cybersecurity tool that detects unauthorized changes to files and directories. This project monitors selected files by generating cryptographic hashes and comparing them against a trusted baseline to identify modifications, deletions, or new files.

The purpose of this project is to understand important cybersecurity concepts such as **hashing algorithms, integrity verification, security monitoring, and threat detection**.

---

## 📌 Project Description

File Integrity Monitoring is commonly used by security teams to protect critical systems from unauthorized modifications.

This implementation works by:

1. Creating a trusted baseline of file hashes.
2. Storing the original integrity state of monitored files.
3. Continuously comparing current file hashes with the baseline.
4. Alerting users when changes are detected.

A mismatch between stored and current hashes indicates that a file may have been modified.

---

## ✨ Features

### File Monitoring
- Monitor selected files and directories
- Detect modified files
- Detect deleted files
- Detect newly created files

### Security Features
- SHA-based cryptographic hashing
- Baseline integrity verification
- Change detection alerts
- Cross-platform support

---

## 🛠️ Technologies Used

- Python
- PowerShell
- Bash Script
- SHA Hash Algorithms
- File System Operations

---

## 📂 Project Structure

```
File-Integrity-Monitor/
│
├── basicFim.py        # Python implementation
├── basicFim.ps1       # PowerShell implementation
├── basicFim.sh        # Bash/Linux implementation
└── README.md          # Documentation
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/ANU123-byte131/file-integrity-monitor.git
```

Navigate to the project directory:

```bash
cd File-Integrity-Monitor
```

---

# ▶️ Usage

The program provides two main options:

### 1. Create New Baseline

Creates a trusted snapshot of the selected directory.

Example:

```
File1.txt → SHA256 Hash
File2.txt → SHA256 Hash
```

---

### 2. Monitor Existing Baseline

Compares the current state of files against the stored baseline.

If changes are detected:

```
ALERT:
File modified

example.txt

Integrity Check Failed
```

---

# Running the Project

## Python Version

Run:

```bash
python basicFim.py
```

---

## PowerShell Version (Windows)

Open PowerShell:

```powershell
cd File-Integrity-Monitor
```

Execute:

```powershell
.\basicFim.ps1
```

---

## Bash Version (Linux/macOS)

Give execution permission:

```bash
chmod +x basicFim.sh
```

Run:

```bash
./basicFim.sh
```

---

# 🔍 How It Works

```
Select Directory
        |
        ↓
Generate File Hashes
        |
        ↓
Create Trusted Baseline
        |
        ↓
Monitor Files
        |
        ↓
Compare Hash Values
        |
        ↓
Generate Security Alert
```

---

# 🎯 Real-World Applications

File Integrity Monitoring is used for:

- Detecting unauthorized system changes
- Protecting sensitive files
- Malware detection
- Server security monitoring
- Compliance auditing
- Incident response investigations

---

# 📚 Cybersecurity Concepts Learned

This project demonstrates:

### Cryptography
- Hash functions
- SHA algorithms
- File fingerprinting

### Security Monitoring
- Integrity checking
- Change detection
- Security alerts

### Automation
- Python scripting
- PowerShell automation
- Linux shell scripting

---

# 🚀 Future Improvements

Planned enhancements:

- Real-time monitoring using file system events
- Email and notification alerts
- Database-based hash storage
- Web-based monitoring dashboard
- Detailed security reports
- User authentication

---

# 🧪 Testing

To test the project:

1. Select a test directory.
2. Create a baseline.
3. Modify or delete a file.
4. Run monitoring again.

Expected output:

```
File Changed:
test.txt

Status:
Modification Detected
```

---

# ⚠️ Disclaimer

This project is developed for educational purposes and authorized security testing only.

Do not monitor files or systems without proper permission.

---

# 👨‍💻 Author

**ANU123-byte131**

GitHub:
https://github.com/ANU123-byte131

---

# ⭐ Acknowledgment

Inspired by cybersecurity learning resources and open-source educational projects.
