# Weekly Backup & File Organizer Script (PowerShell)

## Overview
This PowerShell script automatically organizes your files and creates a weekly rotating backup. It is designed to keep your Desktop neat and your important files safe.

### Features
- **Organize Files by Type**
  - Documents (`.docx`, `.pdf`, `.pptx`, `.xlsx`, `.txt`) → separate folders under `Documents/`
  - Images (`.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`) → separate folders under `Images/`

- **Weekly Rotating Backup**
  - Creates a backup folder on the Desktop: `Backup/`
  - Inside `Backup/`, folders are named by **day of the week + date**:
    ```
    Monday 02092026
    Tuesday 02092026
    ...
    ```
  - If a folder for the same day exists next week, it will be **overwritten** automatically.
  
- **Automation Ready**
  - Can be scheduled via Windows Task Scheduler (e.g., daily at 5PM)
  - Ensures files are backed up before being moved to organized folders

## Folder Structure After Running

