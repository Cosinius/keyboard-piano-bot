# Keyboard Piano Simulator 🎹

⚠️ IMPORTANT NOTICE ABOUT THE EXE FILE ⚠️
YOU NEED TO UNZIP THE RAR FILE TO RUN THE EXE!

IF YOU DOWNLOAD THE EXECUTABLE AS A RAR OR ZIP ARCHIVE, PLEASE EXTRACT IT FIRST BEFORE TRYING TO RUN THE PROGRAM.

WHY VIRUSTOTAL SHOWS "SUSPICIOUS ARCHIVE"?
VIRUSTOTAL MAY FLAG THE FILE AS A "SUSPICIOUS ARCHIVE" BECAUSE IT DETECTS THE EXECUTABLE INSIDE A COMPRESSED PACKAGE (RAR OR ZIP).

THIS IS A COMMON FALSE POSITIVE WITH PACKAGED FILES, ESPECIALLY FOR PYTHON-BASED EXES CREATED WITH TOOLS LIKE PYINSTALLER OR SIMILAR.

THIS DOES NOT MEAN THE FILE CONTAINS A VIRUS OR MALWARE. THE PROGRAM IS 100% SAFE AND OPEN SOURCE.

HOW TO USE THE FILE SAFELY
DOWNLOAD THE FILE FROM THIS REPOSITORY OR THE OFFICIAL GITHUB RELEASES PAGE.

ALWAYS EXTRACT THE ARCHIVE BEFORE RUNNING THE EXECUTABLE.

IF YOU HAVE ANY SECURITY CONCERNS, YOU CAN REVIEW THE SOURCE CODE DIRECTLY OR RUN THE SCRIPT IN PYTHON.

TRUST AND TRANSPARENCY
THIS PROJECT IS OPEN SOURCE AND CREATED FOR EDUCATIONAL AND ENTERTAINMENT PURPOSES.
IF YOU HAVE ANY QUESTIONS OR DOUBTS, PLEASE OPEN AN ISSUE OR CONTACT ME DIRECTLY.

THANK YOU FOR YOUR TRUST! 🙏

A BPM-based automatic keyboard piano simulator built with Python.

This tool is designed to simulate keypresses on virtual piano websites or browser-based rhythm games. It does not produce any sound, only simulates key presses based on given note sheets.

## 🛠️ Features

- ⌨️ Automatically presses keys according to written notes
- 🎵 BPM and speed correction support for accurate timing
- 🎮 Compatible with virtual piano sites and browser games
- 💤 Can be used as an **AFK bot** for online games
- 💡 Shift support for capital letters and symbols

## 🔍 Example Uses

- **Playing songs** on [virtualpiano.net](https://virtualpiano.net/) and similar sites
- **On Roblox piano games
- **Bypassing AFK detection** in games (use input like `w|||||||w`)
- **Simulating keyboard macros** for testing or automation

## ⚙️ Settings

- **BPM (Beats Per Minute)**: Controls note speed.
- **Speed Correction**: Fine-tunes the tempo. If notes play too fast or too slow:
  - Increase towards `1` to **slow down**
  - Decrease towards `0` to **speed up**
  - Example: `0.35` works well for most songs.

### AFK Bot Settings

To use this as an AFK bot:
BPM: 10
Speed Correction: 1
Note Sheet: w|||||||w

This simulates pressing `w`, waiting a bit, and pressing again—commonly used to bypass AFK warnings.

## 🖥️ How to Use

1. Run the Python script:
    ```bash
    python keyboard_simulator.py
    ```

2. Paste or type your note sheet.

3. Adjust BPM and speed correction.

4. Press `▶ Start` or `F8` to begin playback.

5. Press `■ Stop` or `F8` again to stop.

## 📌 Notes Syntax

- Single note: `a b c D E`
- Chords (multiple keys): `[asd] [ASD]`
- Delay/pause: `|` or `-`

## ⚠️ Disclaimer

This software only simulates keyboard input. It is intended for educational and entertainment purposes. Misuse of automated input tools in online games may violate terms of service.

---

**Version:** v1.0.0 (2025-07-28)  
Made with ❤️ in Python and Tkinter
