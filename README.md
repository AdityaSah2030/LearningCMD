# Windows CMD Commands Guide

This repository contains a collection of essential Windows Command Prompt (CMD) commands, structured for easy reference.

---

## 🚀 Navigation Commands

| Command | Description |
|---------|-------------|
| `cd <name>` | Change directory |
| `cd ..` | Go back one directory |
| `cd Desktop\Videos` | Move ahead two steps into the directory |
| `cd ../..` | Go back two directories |
| `TAB` | Auto-complete directory/file names |
| `HOME` | Move cursor to the start of the command |
| `END` | Move cursor to the end of the command |
| `CTRL + ←` | Jump one word at a time |
| `CTRL + →` | Jump one word forward |
| `CTRL + C` | Terminate a running command |
| `CTRL + Z` | Suspend a process |
| `↑ / ↓` | Navigate through command history |

---

## 📁 Directory Management

| Command | Description |
|---------|-------------|
| `dir` | Show all directories |
| `dir /a` | Show all directories including hidden files |
| `dir /s` | Show directory contents recursively |

---

## 📂 Creating & Removing Directories

| Command | Description |
|---------|-------------|
| `mkdir <folderName>` | Create a new directory |
| `rmdir <folderName>` | Remove empty directory |
| `rmdir /s <folderName>` | Remove directory including files within it |
| `del /f /q <fileName>` | Force delete a file |

---

## 📜 Opening Files & History

| Command | Description |
|---------|-------------|
| `cls` | Clear screen |
| `dir *.png` | Show all PNG files in the directory |
| `start <fileName>` | Open a file with its default program |
| `more <fileName>` | View file contents page by page |

---

## 🌐 IP Configuration

| Command | Description |
|---------|-------------|
| `ipconfig /?` | Help command for IP configuration |
| `ipconfig` | Show IP configuration information |
| `ipconfig /all` | Show detailed network information |
| `ipconfig /renew` | Renew all network adapters |
| `ipconfig /release Con` | Release all matching connections |
| `ipconfig /flushdns` | Clear DNS cache |
| `ipconfig /allcompartments /all` | Show detailed information about all compartments |

---

## 🛤 Path Variables

| Command | Description |
|---------|-------------|
| `cd "C:\Program Files\Blah Blah"` | Show absolute path |
| `path` | Show Windows system path |
| `set PATH=%PATH%;C:\NewPath` | Temporarily add a directory to the system path |

---

## 💾 Drive Management

| Command | Description |
|---------|-------------|
| `wmic logicaldisk get name` | Show all drive names |
| `D:` | Switch to the D drive |
| `tree` | Display directory structure in a tree format |
| `diskpart` | Open disk partition manager |

---

## 🎨 CMD Colors

| Command | Description |
|---------|-------------|
| `color XY` | Change CMD color where X is background and Y is foreground |
| `color` | Reset colors |
| `color /?` | Help command for color options |

---

## 🔐 File Attributes

| Command | Description |
|---------|-------------|
| `attrib /?` | Help command for attributes |
| `attrib +R` | Set file to Read-Only |
| `attrib -R` | Remove Read-Only attribute |
| `attrib +H` | Hide a file |
| `attrib -H` | Unhide a file |
| `attrib /S /D` | Process files and directories recursively |

---

## 🗑 Delete & Append Files

| Command | Description |
|---------|-------------|
| `del <fileName.extension>` | Delete a file |
| `del /q /s <fileName>` | Quietly delete a file and suppress prompts |
| `type <fileName.txt>` | Display file content |
| `echo blahBlah > <fileName.txt>` | Overwrite text file |
| `echo blahBlah >> <fileName.txt>` | Append text to file |
| `dir > abc.txt` | Save directory listing to file |

---

## 📋 Copy & Move Files

| Command | Description |
|---------|-------------|
| `copy abc.txt testFolder` | Copy a file to a folder |
| `xcopy Apple Banana` | Copy files from Apple to Banana |
| `xcopy Apple Banana /s` | Copy files and subdirectories |
| `move Apple Banana` | Move folder Apple inside Banana |
| `rename Banana Mango` | Rename Banana to Mango |
| `xcopy /?` | Help command for xcopy |
| `robocopy /?` | Help command for robocopy (more advanced file copying) |

---

## 🔗 Contributing

Feel free to contribute additional CMD commands by submitting a pull request! 🚀

---

## 📢 Acknowledgements

Inspired by Windows Command Prompt power users and enthusiasts!
