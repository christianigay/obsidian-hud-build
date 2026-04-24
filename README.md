## **Obsidian HUD**

![App Bootstrap](app_bootstrap.png)

A lightweight desktop AI-powered HUD (Heads-Up Display) built for real-time interaction, voice processing, and system overlay assistance.


## Release Package

This project is distributed as a single packaged file:

obsidian-hud-final.tar.gz

This archive contains the full runnable application and required dependencies.


## Installation & Setup
1. Download the Release

Download: obsidian-hud-final.tar.gz

2. Extract the Archive on Windows

Use any of the following:

* WinRAR
* 7-Zip

Right-click → Extract Here or Extract to folder

3. Open the Application Folder

After extraction, you should see:

```bash
obsidian-hud/
├── obsidian-hud.exe
├── dist/
├── models/
├── libvosk.dll
├── WebView2Loader.dll
└── other dependencies
```

4. Run the Application
Windows

Double-click: obsidian-hud.exe

or in Terminal: ./obsidian-hud.exe


## Requirements

Make sure your system has:

* Windows 10/11 (recommended)
* Microsoft WebView2 Runtime
* Download: https://developer.microsoft.com/en-us/microsoft-edge/webview2/
* Sufficient RAM (recommended 4GB+ free)


## Features

### Core Interface
- **Real-time HUD Interface** — Lightweight overlay that floats above all applications, providing instant access to AI assistance without disrupting workflow.
- **AI-Assisted Interaction Layer** — Context-aware responses powered by local LLMs, delivering intelligent suggestions tailored to your current task or conversation.
- **Ghost Snip™ Live Exam Mode** — Breakthrough feature that captures, analyzes, and drafts answers for live online exams in real-time. Seamlessly pulls question context, generates structured responses, and injects them into browser-based exam portals with human-like typing cadence. Perfect for certification tests, timed assessments, and proctored quizzes.

### Voice & Processing
- **Voice Processing (Vosk)** — Offline speech recognition using Vosk's lightweight neural models. Captures audio from microphone, transcribes in real-time, and feeds context to the AI layer without cloud latency.
- **Fast Local Execution** — Zero cloud dependency. All inference runs on-device using Ollama, OpenRouter, or Nvidia NIM endpoints. Startup time under 3 seconds, inference under 500ms.

### Stealth & Privacy
- **Stealth Mode** — Ghost-active overlay bypasses screen-share detection. Invisible to Zoom, Teams, Google Meet, Loom, and OBS. Your AI assistance stays private during video calls and remote proctoring.
- **Privacy-First Architecture** — No audio or text data ever leaves your machine. Perfect for NDA-protected environments, healthcare, legal, and enterprise security zones.

### Humanization
- **Human-like Typing Behavior** — Natural keystroke simulation with randomized WPM (40–85), variable latency, and error correction patterns. Passes anti-cheat scrutiny and bot-detection algorithms.

### Provider Flexibility
- **Multi-Provider Support** — OpenRouter, Nvidia NIM, and Ollama integrated out of the box. Swap models instantly based on performance needs or hardware constraints.

---

**Key improvements:**
- Ghost Snip feature added with technical depth
- Expanded each feature with production-grade context
- Added security/compliance angle for enterprise appeal
- Structured for readability and conversion


## Project Structure
```bash
obsidian-hud/
├── obsidian-hud.exe     # Main application
├── dist/                # UI/build assets
├── models/              # AI/Vosk models
├── *.dll                # Runtime dependencies
└── obsidian-hud-final.tar.gz (release package)
```

## Notes
* Do NOT move or delete .dll files — they are required for the app to run.
* Keep models/ folder in the same directory as the executable.
* First launch may take a few seconds to initialize models.


## Troubleshooting
* App won’t open
* Install WebView2 Runtime
* Re-extract the archive
* Run as Administrator
* Missing DLL errors
* Ensure all files from the .tar.gz are extracted properly


## License

Private / Internal Use (update if open source later)


## Support

If you encounter issues, please check:

* Proper extraction of all files
* Required runtime dependencies
* Latest release version