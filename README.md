# MSFS Downloader Installer (Unofficial)

This is an experimental graphical installer/downloader for Microsoft Flight Simulator 2020 content files, designed to replace the slow and buggy default installer.

> ⚠️ **Status: UI Functional — Backend Not Implemented Yet**  
> The application launches correctly with a working graphical interface (PyQt6),  
> but downloading, extraction, and file operations are **not yet implemented or stable**.

---

## 🧰 Features (Planned)

- Download MSFS files in chunks (e.g., `Official.zip.0001` to `Official.zip.2407`)
- Verify disk space (600 GB required, SSD recommended)
- Optional RAM usage limit (8 GB max)
- Parallel downloads (multi-threaded)
- Real-time logs and progress bars
- Automatic unzipping after download
- Modern UI using PyQt6

---

## 🔧 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/msfs-installer.git
cd msfs-installer

### 2. Install dependencies
```bash
pip install pyqt6 requests psutil


