Obsidian HUD

A lightweight desktop AI-powered HUD (Heads-Up Display) built for real-time interaction, voice processing, and system overlay assistance.

Release Package

This project is distributed as a single packaged file:

obsidian-hud-final.tar.gz

This archive contains the full runnable application and required dependencies.

Installation & Setup
1. Download the Release

Download:

obsidian-hud-final.tar.gz
2. Extract the Archive
Windows

Use any of the following:

WinRAR
7-Zip

Right-click → Extract Here or Extract to folder

Linux / WSL / macOS

Run:

tar -xvzf obsidian-hud-final.tar.gz
3. Open the Application Folder

After extraction, you should see:

obsidian-hud/
├── obsidian-hud.exe
├── dist/
├── models/
├── libvosk.dll
├── WebView2Loader.dll
└── other dependencies
4. Run the Application

Windows
Double-click:

obsidian-hud.exe

Terminal
./obsidian-hud.exe


⚙️ Requirements


Make sure your system has:

Windows 10/11 (recommended)
Microsoft WebView2 Runtime
Download: https://developer.microsoft.com/en-us/microsoft-edge/webview2/
Sufficient RAM (recommended 4GB+ free)


Features
Real-time HUD interface
AI-assisted interaction layer
Voice processing support (Vosk)
Lightweight desktop overlay system
Fast local execution (no cloud dependency)


Project Structure
obsidian-hud/
├── obsidian-hud.exe     # Main application
├── dist/                # UI/build assets
├── models/              # AI/Vosk models
├── *.dll                # Runtime dependencies
└── obsidian-hud-final.tar.gz (release package)


⚠️ Notes
Do NOT move or delete .dll files — they are required for the app to run.
Keep models/ folder in the same directory as the executable.
First launch may take a few seconds to initialize models.


Troubleshooting
App won’t open
Install WebView2 Runtime
Re-extract the archive
Run as Administrator
Missing DLL errors
Ensure all files from the .tar.gz are extracted properly


License

Private / Internal Use (update if open source later)

Support

If you encounter issues, please check:

Proper extraction of all files
Required runtime dependencies
Latest release version
Send Official Facebook Group from the App
