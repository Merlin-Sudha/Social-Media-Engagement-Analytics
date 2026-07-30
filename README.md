# Social-Media-Engagement-Analytics
# 📂 Python File Backup Automation

## 📌 Project Overview
This project demonstrates a simple Python automation script that automatically moves files from a source folder to a destination (backup) folder. It helps automate file management tasks, reducing manual effort and improving productivity.

## 🎯 Objectives
- Automate file movement using Python.
- Learn file handling and directory management.
- Reduce manual work through automation.
- Understand the use of Python's built-in modules.

## 🛠️ Technologies Used
- Python 3
- os Module
- shutil Module
- Google Colab / Jupyter Notebook

## 📂 Project Structure
```
Python-File-Backup-Automation/
│
├── automation.py
├── README.md
└── sample_output.png (Optional)
```

## 🚀 Features
- Automatically reads all files from the source folder.
- Moves files to a backup folder.
- Uses Python built-in libraries.
- Simple and beginner-friendly automation project.

## 📜 Code
```python
import os
import shutil

source = "Downloads"
destination = "Backup"

for file in os.listdir(source):
    shutil.move(os.path.join(source, file), destination)
```

## 📖 How It Works
1. Import the `os` and `shutil` libraries.
2. Specify the source folder containing files.
3. Specify the destination (backup) folder.
4. Read all files from the source folder.
5. Move each file to the backup folder automatically.

## ▶️ How to Run
1. Install Python 3.
2. Create two folders:
   - Downloads
   - Backup
3. Place files inside the Downloads folder.
4. Run the Python script.
5. All files will be moved to the Backup folder.

## 📊 Output
**Before Execution**
```
Downloads/
├── file1.pdf
├── image.png
├── notes.txt
```

**After Execution**
```
Downloads/
(Empty)

Backup/
├── file1.pdf
├── image.png
├── notes.txt
```

## 💡 Applications
- File backup automation
- Office document management
- Desktop cleanup
- Download folder organization
- Basic automation learning

## 📚 Learning Outcomes
- Python file handling
- Directory management
- Automation using Python
- Working with `os` and `shutil` modules

## 🔮 Future Enhancements
- Organize files by extension.
- Automatically create folders based on file types.
- Add logging functionality.
- Schedule automatic backups.
- Add a graphical user interface (GUI).

## 👩‍💻 Author
**Merlin Sudha**

---
⭐ If you found this project helpful, consider giving it a Star on GitHub!
