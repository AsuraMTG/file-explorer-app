# File Explorer-like Application in C# WinForms

## Description

This is a simple **File Explorer-like** application built using **C# WinForms**. The application allows users to:

- View files and folders in a directory
- Open files with their default associated programs (e.g., `.exe`, `.txt`, `.png`)
- Create new files
- Rename, delete, and move files
- Navigate through directories and perform basic file operations
- Search for files by name or extension
- Start automatically when Windows starts (with options for adding/removing from startup)

This app is designed to help users manage their files and folders easily while providing basic file manipulation features typically found in a standard file explorer.

## Features

### File Operations:
- **Open Files**: Open files with their associated programs (e.g., `.exe`, `.png`, `.txt`).
- **Create Files**: Create new files, including empty files or with custom content (e.g., text files).
- **Delete Files**: Delete selected files.
- **Rename Files**: Rename files.
- **Move Files**: Move files between directories.

### Directory Operations:
- **Navigate Directories**: Browse directories and view their contents.
- **Search Files**: Search for files by name or extension.
- **Show Directory Tree**: Visualize the directory structure using a `TreeView` or `ListView`.

### Startup Integration:
- **Auto-Start with Windows**: Option to add the application to the Startup folder or Windows registry so it launches automatically when Windows starts.
- **Remove from Startup**: Option to remove the application from the Startup folder or registry.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AsuraMTG/file-explorer-app.git
