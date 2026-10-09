# 📁 Auto File Organizer

**Auto File Organizer** is a lightweight Windows desktop application built with Python and Tkinter. It helps organize files into category folders based on their file extensions.

## ✨ Features

* 📂 Select a folder to organize
* 👀 Preview planned file moves before organizing
* 🗂️ Automatically categorize files by extension
* 🛡️ Avoid overwriting existing files
* 📝 Rename files when filename conflicts occur
* 📊 View the results of an organization operation
* ↩️ Undo the most recent supported operation
* 💻 Simple Windows desktop interface
* 🔒 Designed to work offline

## 📦 File Categories

| Category   | Supported Extensions                                      |
| ---------- | --------------------------------------------------------- |
| Images     | `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.bmp`          |
| Documents  | `.pdf`, `.doc`, `.docx`, `.txt`, `.xlsx`, `.pptx`, `.csv` |
| Videos     | `.mp4`, `.mkv`, `.avi`, `.mov`                            |
| Music      | `.mp3`, `.wav`, `.flac`, `.m4a`                           |
| Installers | `.exe`, `.msi`                                            |
| Archives   | `.zip`, `.rar`, `.7z`                                     |
| Others     | All other file extensions                                 |

## 🖥️ Download for Windows

1. Open the **Releases** section of this GitHub repository.
2. Download `AutoFileOrganizer.exe` from the latest release.
3. Open the downloaded application on Windows.
4. Select a folder and review the planned file moves.
5. Run the organization operation after reviewing the preview.

**Important:** Test the application with sample files first. Keep backups of important data before organizing real folders.

## 🚀 Run from Source

### Requirements

* Windows 10 or Windows 11
* Python installed on your computer

### Steps

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Open a terminal in the project directory.
4. Run the application:

   ```bash
   python auto_file_organizer.py
   ```

## 🔨 Build the Windows Executable

Install PyInstaller:

```bash
python -m pip install pyinstaller
```

Build the application:

```bash
python -m PyInstaller --noconfirm --clean --onefile --windowed --name AutoFileOrganizer auto_file_organizer.py
```

After a successful build, find the executable in the `dist` folder:

`dist/AutoFileOrganizer.exe`

## 🛡️ Safety

* Review the preview before moving files.
* Use a test folder before organizing important data.
* Keep backups of files you cannot afford to lose.
* Verify the results before relying on the undo feature.

## 🧰 Technologies Used

* Python
* Tkinter
* `os` and `shutil`
* JSON for undo-operation logging
* PyInstaller for Windows executable packaging

## 📌 Project Status

This project is intended for Windows 10 and Windows 11. Test the application in your own environment before relying on it for important file operations.

## 🤝 Contributions

Suggestions, bug reports, and improvements are welcome. Please describe any issues clearly and include steps to reproduce them.

## 📄 License

No license has been selected for this project yet. Unless a license is added, others do not automatically receive permission to reuse, modify, or redistribute the code.

---

**Made with Python for Windows.**
