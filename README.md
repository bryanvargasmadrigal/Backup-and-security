<h1 align="center">🔐 Secure Backup Automation</h1>
<h3 align="center">PowerShell + 7-Zip | Encrypted Backup System</h3>

<p align="center">
Automated and encrypted backup solution using PowerShell scripting and 7-Zip.
</p>

## 📌 Overview

This project implements a secure and automated backup system that compresses and encrypts files using PowerShell and 7-Zip.

It is designed to ensure data protection through encryption and scheduled execution.

---

## ⚙️ Features

* 🔐 Encrypted backups using 7-Zip
* ⏱️ Automated execution with Task Scheduler
* 📁 Custom source and destination folders
* 💻 Lightweight and easy to configure

---

## 🛠️ Technologies Used

* PowerShell
* 7-Zip
* Windows Task Scheduler

---

## 📂 Project Structure

```bash
project/
│── backup.ps1
│── origen/      # Files to backup
│── backup/      # Encrypted backups
│── banner.png
```

---

## ⚙️ Setup

### 1. Create folders

Create two directories:

* `origen` → files to backup
* `backup` → encrypted backups

---

### 2. Install 7-Zip

Install 7-Zip and verify installation path:

```bash
C:\Program Files\7-Zip\7z.exe
```

---

### 3. PowerShell Script

Create a file named:

```bash
backup.ps1
```

Add your backup script here.

---

### 4. Automate Backup

Use Windows Task Scheduler:

* Create a new task
* Set trigger (daily or desired interval)
* Configure execution time

---

### 5. Access Backups

To extract files:

* Open 7-Zip
* Navigate to backup file
* Enter the configured password

---

## 🔐 Security

* Files are encrypted before storage
* Password protection required for access
* Reduces risk of data loss or unauthorized access

---

## 🚀 Future Improvements

* Logging system for backup status
* Error handling and alerts
* Integration with remote storage

---

## 👨‍💻 Author

Brayan Vargas
Cybersecurity & Systems
