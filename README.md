# 🧹 CleanSweep v1.0 — Automatic File Cleanup Tool

CleanSweep is a lightweight Windows tool that helps you delete old files based on file type and age — while keeping the **most recent one safe**.

I built it for my personal use to automate cleaning backup/log folders. Now, I’m sharing it freely in case it helps others too.

---

## 🔧 What It Does

- Automatically deletes old files from a specified folder  
- Skips the **most recent file** to avoid data loss  
- Logs all actions and errors to:  
  `C:\Logs\AutoDeteFile\Log.txt`

---

## 🛠 Configuration

1. Open `settings.json` in any text editor
2. Change the folder path, file extensions, and retention days

**Example:**
```json
{
  "FolderDirectory": "C:\\DatabaseBackup",
  "FileExtensions": [".bak", ".log"],
  "RetentionDays": 7
}
