# ◉ Cloud J.A.R.V.I.S. — 100% FREE Potato-PC Windows Edition ($0 / No Credit Card)

An ultra-lightweight desktop **J.A.R.V.I.S.** voice & vision assistant engineered specifically for **low-spec ("potato") Windows 10/11 PCs** — now running **100% FREE ($0.00, NO credit card required)**.

Instead of melting your PC with 6 GB local LLMs, PyTorch, or Electron apps, **100% of AI reasoning, speech recognition, screen vision, and British neural voice synthesis run in Free Cloud APIs** while a tiny native Python + Win32 client controls your Windows PC locally.

---

## 💸 How Is Every Piece 100% Free ($0 / No Card)?

| Layer | Powered By | Cost / Signup |
| :--- | :--- | :--- |
| **Brain + 20 PC Tools + Screen Vision** | **Google Gemini Free Tier** (`gemini-2.5-flash`) **OR** **Groq Free Cloud** (`llama-3.3-70b` / `llama-4-scout`) | **$0.00 Free** — 15-second Google login, **NO credit card required** |
| **Speech-to-Text (Ears)** | **Groq Free `whisper-large-v3-turbo`** + **Zero-Key Google Web Speech** | **$0.00 Free** (works even with zero STT key!) |
| **British J.A.R.V.I.S. Voice (Mouth)** | **Microsoft Neural `edge-tts`** (`en-GB-RyanNeural`) + Windows SAPI5 offline backup | **$0.00 Free — NO API key needed at all!** |
| **Web Search & Weather** | Built-in DuckDuckGo + Met.no Weather | **$0.00 Free — NO API key needed!** |
| **Local PC Footprint** | Native Win32 + Tkinter Mini-HUD | **~40–64 MB RAM, 0.00% idle CPU, 0% GPU** |

---

## 🚀 30-Second Windows Quick Start

1. **Install Python 3.9+** on Windows ([python.org/downloads](https://www.python.org/downloads/) — check **"Add python.exe to PATH"** during setup).
2. Extract this folder anywhere (e.g., `Desktop\cloud-jarvis`).
3. **Double-click `install_and_run.bat`**.
   - Automatically creates `.venv`, installs the lightweight packages once, and opens the **Floating Arc-Reactor HUD** in the bottom-right corner of your desktop.
4. In the **100% Free Cloud Setup** popup that opens:
   - Click **`🔑 Get FREE Gemini Key ↗`** ([aistudio.google.com/apikey](https://aistudio.google.com/apikey)) **OR** **`⚡ Get FREE Groq Key ↗`** ([console.groq.com/keys](https://console.groq.com/keys)) — sign in with Google (**no credit card asked!**), copy your free key (`AIza...` or `gsk_...`), paste it in, and click **`✔ Verify & Activate Free JARVIS`**!
   - *(Pro tip: Paste **both** free keys if you want Groq's 500 tok/sec speed + Whisper AND automatic failover to Gemini 2.5 Flash!)*

### Optional Launchers
- **`run_jarvis_silent.vbs`** — Runs the Floating HUD silently with **zero black Command Prompt window** (put a shortcut in `Win+R` → `shell:startup` to boot JARVIS with Windows).
- **`run_cli.bat`** — Ultra-lean terminal-only mode (`--cli`).

---

## ⌨️ Global Windows Hotkeys (0.00% Idle CPU, No Admin Needed)

| Shortcut | Action |
| :--- | :--- |
| **`Alt + J`** or **`F9`** | **Push-to-Talk / Tap-to-Talk** — Chimes, listens until you finish speaking, executes & replies in British neural voice |
| **`Ctrl + Alt + S`** | **Free Cloud Screen Vision** — Captures your screen (~80 KB JPEG) and explains visible errors, code, or UI |
| **`Ctrl + Alt + H`** | **Toggle Hands-Free Mode** — Local energy VAD listens for *"Jarvis..."* with an 8s follow-up conversation window |
| **`Ctrl + Alt + X`** | **Interrupt Speech** — Immediately stops JARVIS mid-sentence |

---

## 🛠 Example Commands You Can Say Out Loud

- **PC & App Control:** *"Open Spotify and set the volume to 40 percent."* / *"Launch VS Code."* / *"Open Bluetooth settings."* / *"Pause the music."* / *"Set brightness to 60 percent."* / *"Minimize all windows."*
- **Potato-PC RAM Booster:** *"Why is my PC lagging?"* / *"Boost my RAM"* (safely trims idle working sets via Windows `EmptyWorkingSet` without closing your apps!) / *"Close Discord to free memory."*
- **Free Screen Vision & Clipboard:** *"Look at my screen and help me fix this error."* / *"Summarize what I just copied to my clipboard."*
- **Files, Web, Weather, Memory & Timers:** *"Find my resume PDF in Downloads and open it."* / *"What's the weather in Vijayawada?"* / *"Remember my laptop has 4GB RAM."* / *"Set a timer for 10 minutes."*
