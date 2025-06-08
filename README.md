# convert-py-to-exe

This project shows how to convert a Python script into a standalone Windows executable (`.exe`) using [PyInstaller](https://pyinstaller.org/).

## 🚀 Installation

First, install PyInstaller using pip:

1. pip install pyinstaller
   
Example: Convert .py to .exe
Make sure you're in the same directory as your .py file.

Open a terminal or command prompt and run:
pyinstaller --onefile Filename.py

--onefile: Creates a single .exe file (instead of multiple files).

You’ll find your .exe in the dist/ folder.
