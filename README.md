# 🛡️ BackTrack Pro - Intelligent Backup Manager

**Version:** 1.0.0  
**Author:** Ansh Gautam  
**Build Type:** `.exe` release (Windows)

---

## 📦 About

**BackTrack Pro** is a **powerful GUI-based intelligent backup solution** designed to overcome the limitations of traditional file backup methods. It provides a modern, visual interface for selecting directories, detecting file changes (new, modified, deleted), and seamlessly performing incremental backups—all without user guesswork.

---

## 🚀 Features

- ✅ **Graphical Interface (Tkinter-based)** – No command-line complexity.
- 🔍 **Change Detection** – Uses MD5 hashing to identify:
  - New files
  - Modified files
  - Deleted files
- 📁 **Multi-Source Support** – Add multiple source directories.
- 📦 **Destination Backup Folder** – Easily browse and select output location.
- 📊 **Detailed Log History** – Every backup is logged with:
  - Timestamp
  - File count
  - Backup size
  - Completion status
- 🧠 **Incremental Smart Backup** – Only backs up files that have changed.
- 📈 **Progress Tracking** – Visual progress bar for scan and backup operations.
- 🗂️ **Tabbed Views** – Separate view tabs for:
  - New Files
  - Modified Files
  - Deleted Files
- 📝 **Persistent Backup Records** – Logs and hash metadata saved for future sessions.

---

## 🆚 Traditional Methods vs. BackTrack Pro

| Feature                        | Traditional Manual Backup       | **BackTrack Pro**                        |
|-------------------------------|----------------------------------|------------------------------------------|
| Interface                     | Manual/CLI                       | Fully GUI (Tkinter)                      |
| Change Detection              | None or date-based               | **Hash-based detection** (highly accurate) |
| Incremental Backup            | Rare or script-based             | **Built-in automatic incremental**       |
| History Logging               | Manual                           | **JSON-based persistent logs**           |
| Error Handling                | Minimal                          | **Robust error detection**               |
| Usability                     | Tedious                          | **One-click operation**                  |
| Multi-Directory Support       | Difficult                        | **Native support**                       |

---

## 🧩 How It Works

1. **Select source directories** – Multiple allowed.
2. **Choose destination backup folder** – The target where backups will be stored.
3. **Scan for changes** – Detects new, modified, and deleted files.
4. **Review file changes** – View categorized changes in UI tabs.
5. **Start backup** – Backs up only necessary files.
6. **View logs** – History of backups available under the "Backup History" tab.

---

## 🛠️ Installation

> 💡 This tool is distributed as a **Windows `.exe` file** on the GitHub [Releases](https://github.com/Ansh-Gautam-1337/BackTrack-Pro/releases) page.

### ✅ To Run:
1. Download the latest `.exe` from [Releases](https://github.com/Ansh-Gautam-1337/BackTrack-Pro/releases).
2. Double-click to run — no installation required.

---

## 💾 Data Files

BackTrack Pro uses two JSON files to persist data:
- `BackTrack-Pro_logs.json`: Backup history
- `BackTrack-Pro_hashes.json`: File hash metadata for change detection

These are stored in the user’s home directory (e.g., `C:\Users\YourName\`).

---

## 🔐 Privacy & Security

- File content is **never uploaded** or shared externally.
- File hashes are used **only locally** for change tracking.
- All data remains **on your machine**.

---

## 🧰 Tech Stack

- Language: **Python 3.10+**
- GUI: **Tkinter**
- File operations: `os`, `shutil`, `hashlib`
- JSON logs and metadata

---

## 📝 License

MIT License.  
Free for personal and commercial use.

---

## 🤝 Acknowledgments

Developed by **Ansh Gautam** with ❤️  
Special thanks to the open-source community and testers.

---

## 📩 Feedback & Issues

Found a bug or have a feature request?  
Raise an issue [here](https://github.com/Ansh-Gautam-1337/BackTrack-Pro/issues)
