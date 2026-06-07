## **Obsidian HUD**

![App Bootstrap](app_bootstrap.png)

A lightweight desktop AI-powered HUD (Heads-Up Display) built for real-time interaction, voice processing, and system overlay assistance.


## Release Package

This project is distributed as a single packaged file:

```bash
obsidian-hud-final.tar.gz
```

This archive contains the full runnable application and required dependencies.


## Installation & Setup
1. Download the Release

Download: 
```bash 
obsidian-hud-final.tar.gz 
```

2. Extract the Archive on Windows

Use any of the following:

* WinRAR
* 7-Zip
* Or in terminal

```bash
tar -xvf obsidian-hud-final.tar.gz
```

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
**Windows**

Double-click: obsidian-hud.exe

or in Terminal: 
```bash
.\obsidian-hud.exe
```

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

## Presentation Broadcast (NEW)

**Run smooth, real-time presentations across any room — no cables, no setup hassle.**

A built-in **LAN-based screen sharing system** designed for classrooms, teams, and live events.

---

### Instant Setup & Access

* **Live Screen Broadcast** over WiFi/LAN
* **QR Code / Room Code Join** (no installs for viewers)
* Join instantly from mobile or desktop

---

### Smooth & Reliable Performance

* **Low-Latency Streaming** (WebSockets)
* **Performance scales with your network**
* **Live Stats** (FPS, Bitrate, Latency)

---

### Full Presenter Control

* **Multi-Monitor Switching (Real-Time)**
* **Connected Devices Panel** (see all viewers live)

---

### Live Drawing & Annotation (NEW)

* **Draw directly on your screen in real-time**  
* Highlight key points during presentations  
* Use **pen, highlighter, shapes, and text tools**  
* Annotations are **instantly visible to all viewers**  
* Perfect for teaching, walkthroughs, and live explanations  

---

### Built-in File Sharing

* Share **PDFs, images, videos, and documents** during sessions
* Everything in one place — no switching tools

---

### Better Viewing Experience

* **Fullscreen Viewer Mode** (mobile + desktop)
* Clean, distraction-free viewing for your audience

---

### Key Advantage

* **Start a presentation room in 1 click**

### Stealth & Privacy
- **Stealth Mode** — Ghost-active overlay bypasses screen-share detection. Invisible to Zoom, Teams, Google Meet, Loom, and OBS. Your AI assistance stays private during video calls and remote proctoring.
- **Privacy-First Architecture** — No audio or text data ever leaves your machine. Perfect for NDA-protected environments, healthcare, legal, and enterprise security zones.

### Humanization
- **Human-like Typing Behavior** — Natural keystroke simulation with randomized WPM (40–85), variable latency, and error correction patterns. Passes anti-cheat scrutiny and bot-detection algorithms.

### Provider Flexibility
- **Multi-Provider Support** — OpenRouter, Nvidia NIM, and Ollama integrated out of the box. Swap models instantly based on performance needs or hardware constraints.

> **Note:** Paid models from NVIDIA, OpenRouter, and Ollama are **not included** in this license. Any usage is billed separately via your provider accounts.

---

**Key improvements:**
- Ghost Snip feature added with technical depth
- Expanded each feature with production-grade context
- Added security/compliance angle for enterprise appeal
- Structured for readability and conversion

## Activity Management & Live Learning Sessions (NEW)

**Transform Obsidian HUD into a real-time classroom, training, and assessment platform.**

Create rich interactive learning activities and instantly deliver them to connected devices across your network.

---

### Activity Builder

Create and manage learning activities with support for:

* Multiple Choice
* True / False
* Matching
* Fill in the Blank
* Checklist
* Short Answer
* Essay

Each activity supports:

* Custom instructions
* Question images
* Option images
* Question backgrounds
* Activity backgrounds
* Theme customization
* Auto-grading configuration
* Manual grading workflows

---

### Beautiful Themes & Visual Learning

Create immersive learning experiences with:

* Built-in theme library
* Custom color themes
* Activity-wide backgrounds
* Question-specific background overrides
* Rich image support
* Mobile-friendly layouts

Question background priority:

```text
Question Background
       ↓
Activity Background
       ↓
Theme Background
```

---

### Real-Time Activity Sharing

Launch an activity and instantly create a live session.

Participants join through:

* QR Code
* Join Code
* Direct URL

No installation required.

Works on:

* Android
* iPhone
* Tablets
* Laptops
* Desktop Browsers

---

### Interactive Classroom Mode

Perfect for:

* Classroom instruction
* Group discussions
* Review games
* Facilitated learning

Features:

* Host-controlled navigation
* Previous / Next controls
* Live participant monitoring
* Real-time answer tracking
* Immediate feedback
* Automatic scoring

Workflow:

```text
Host Opens Question
        ↓
Participants Answer
        ↓
Submit Answer
        ↓
Instant Feedback
        ↓
Waiting State
        ↓
Host Navigates Next
```

---

### Instant Feedback System

After answer submission:

#### Correct Answers

* Animated success screen
* Green confirmation effects
* Correct answer highlighting
* Success sound effects

#### Incorrect Answers

* Animated feedback screen
* Correct answer display
* Wrong-answer sound effects
* Visual learning reinforcement

#### Partial Credit

* Partial-success feedback
* Score breakdown
* Guided correction display

---

### Built-In Audio Feedback

Interactive activities include real-time audio responses.

Supported feedback sounds:

* Correct Answer
* Incorrect Answer
* Partial Credit
* Submission Received

Features:

* Plays only on participant device
* Optional mute control
* Browser-based audio engine
* Ultra-low latency playback

---

### Assessment Mode

Ideal for:

* Exams
* Quizzes
* Diagnostic tests
* Self-paced learning

Features:

* Participant-controlled navigation
* Auto-save answers
* Resume support
* Question review
* Submission validation
* Locked submissions

Participants can:

* Move freely between questions
* Review previous answers
* Modify answers before submission
* Submit when ready

---

### Auto-Grading Engine

Automatically grades:

* Multiple Choice
* True / False
* Matching
* Fill in the Blank
* Checklist

Supports:

* Partial credit
* Case-sensitive matching
* Multiple accepted answers
* Match-pair scoring

---

### Manual Review System

For advanced assessments:

* Short Answer grading
* Essay grading
* Teacher remarks
* Rubric scoring
* Score recalculation

Results update instantly after grading.

---

### Live Monitoring Dashboard

Track participant activity in real time.

View:

* Connected participants
* Submission progress
* Answer statistics
* Participation rates
* Completion status
* Session analytics

Perfect for classrooms, training rooms, and workshops.

---

### Visual Results Dashboard

Participants receive immediate performance summaries.

Includes:

* Score Gauge
* Progress Charts
* Pie Charts
* Completion Metrics
* Rubric Interpretation

Example:

```text
92% - Outstanding
```

---

### Downloadable Reports

Generate detailed performance reports.

#### Participant Downloads

* PDF Results
* Score Summary
* Question Review

#### Host Downloads

* PDF Reports
* CSV Exports
* Excel Exports

Includes:

* Name
* School
* Grade
* Scores
* Percentages
* Completion Date
* Activity Results

Files are automatically saved to the system Downloads folder.

---

### Multi-Device Architecture

Built using:

* Tauri
* Vue 3
* Rust
* SQLite
* Axum
* WebSockets

Features:

* Real-time synchronization
* LAN-based delivery
* Ultra-fast response times
* Mobile device compatibility
* Offline-friendly architecture

---

### Educational Use Cases

Perfect for:

* Schools
* Universities
* Corporate Training
* Workshops
* Certification Programs
* Live Events
* Team Assessments
* Employee Evaluations

---

### Key Advantage

**Create, share, monitor, assess, and export learning activities from a single application without requiring cloud services or third-party learning platforms.**


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

### App won’t open
- Install WebView2  
- Re-extract archive  
- Run as Administrator  

### Broadcast issues
- Same WiFi/LAN required  
- Check firewall (port 3030)  

### Missing DLL
- Ensure full extraction 


## License

Private / Internal Use (update if open source later)


## Support

If you encounter issues, please check:

* Proper extraction of all files
* Required runtime dependencies
* Latest release version