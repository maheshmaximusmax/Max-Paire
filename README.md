<p align="center">
  <img src="app_icon.png" alt="Max Paire Logo" width="120">
</p>

<h1 align="center">Max Pair</h1>

<p align="center">
  <strong>Connect multiple Bluetooth earbuds to one PC — hear audio on all of them!</strong>
</p>

<p align="center">
  <a href="https://github.com/maheshmaximusmax/max-paire/releases/latest"><img src="https://img.shields.io/github/v/release/maheshmaximusmax/max-paire?style=for-the-badge&color=7C3AED&label=Download" alt="Download"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D4?style=for-the-badge&logo=windows" alt="Windows">
  <img src="https://img.shields.io/badge/Price-Free-00C853?style=for-the-badge" alt="Free">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT License">
</p>

<p align="center">
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-features">Features</a> •
  <a href="#-download">Download</a> •
  <a href="#-how-it-works">How It Works</a> •
  <a href="#-faq">FAQ</a>
</p>

---

## 😤 The Problem

You have **2 Bluetooth earbuds** (or speakers) and want to listen to the **same audio** on both from your Windows PC.

But Windows only lets you play audio on **ONE device at a time!**

## 🎉 The Solution — Max Paire

**Max Paire** mirrors your PC audio to **2, 3, 4, or more** Bluetooth earbuds/speakers at the same time. Zero lag. Clean audio. One click.

> 🎧 Watch a movie with your friend — both wearing your own earbuds  
> 🎵 Play music on two Bluetooth speakers at a party  
> 🎮 Game together with shared audio on separate earbuds  
> 📺 Share YouTube/Netflix audio without splitting earbuds  

---

## 🚀 Quick Start

### For Everyone (No coding needed!)

1. **Download** → Go to [**Releases**](https://github.com/maheshmaximusmax/max-paire/releases/latest) and download `MaxPaire.exe`
2. **Pair** your earbuds in Windows Bluetooth Settings
3. **Run** `MaxPaire.exe` — it auto-detects your earbuds
4. **Click** `Start Sync` — done! Both earbuds play audio! 🎶

That's it. No installation needed. Just download and run.

### Want to install it properly? (Optional)

1. Download `MaxPaire_Installer.zip` from [Releases](https://github.com/maheshmaximusmax/max-paire/releases/latest)
2. Extract and run `INSTALL.bat`
3. Now you have:
   - Desktop shortcut
   - Start Menu entry (search "Max Paire")
   - System tray icon
   - Shows in Add/Remove Programs

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎧 **Multi-Device** | Connect 2, 3, 4+ earbuds or speakers at once |
| ⚡ **Zero Lag** | PortAudio C-level callbacks — audio runs in native code, not Python |
| 🌙 **Dark / Light Theme** | Beautiful modern UI with theme toggle |
| 📌 **System Tray** | Minimizes to tray — always accessible from taskbar |
| 🔄 **Auto-Detect** | Automatically finds your Bluetooth devices |
| 🔊 **Any Brand** | Works with ANY Bluetooth earbuds — Sony, JBL, boAt, AirPods, Samsung, etc. |
| 🆓 **100% Free** | No ads, no premium, no subscription. Free forever. |
| 📦 **Portable** | Single .exe file. No installation required. |
| 🔒 **Safe** | Open source. No data collection. No internet needed. |

---

## 📥 Download

### 👉 [Click here to download MaxPaire.exe](https://github.com/maheshmaximusmax/max-paire/releases/latest)

| File | Description |
|------|-------------|
| `MaxPaire.exe` | Just download and run — works instantly |
| `MaxPaire_Installer.zip` | Includes installer for desktop shortcut + Start Menu |

**Requirements:** Windows 10 or 11. That's it!

---

## 🧠 How It Works

```
Your PC plays audio
       ↓
Windows sends to DEFAULT earbud (Earbud A) ← plays normally
       ↓
Max Paire captures that audio (WASAPI loopback)
       ↓
Sends it to Earbud B, C, D... ← plays the same audio!
       ↓
ALL earbuds hear the same thing! 🎶
```

**In simple words:**
- Earbud A = your normal Windows audio device (plays audio like usual)
- Earbud B, C, D = Max Paire copies the audio and sends it to these
- Result = everyone hears the same thing!

---

## 📖 Step-by-Step Guide (Super Easy!)

### Step 1: Pair Your Earbuds

Open **Windows Settings** → **Bluetooth** → Pair both earbuds one by one.

### Step 2: Set One as Default

Open **Windows Settings** → **Sound** → Set one earbud as your output device.

### Step 3: Open Max Paire

Double-click `MaxPaire.exe`. It will show:
- Your **default earbud** at the top (Earbud A)
- Your **other earbuds** in the list below (auto-detected!)

### Step 4: Click Start Sync

Press the big purple **Start Sync** button. Done! 🎉

Both earbuds now play the same audio. Open YouTube, Spotify, a movie — anything. Both hear it.

### Step 5: Enjoy!

- To stop: click **Stop Sync**
- To minimize: click **X** (goes to system tray)
- To switch theme: use the **Dark/Light toggle** at the top

---

## ❓ FAQ

<details>
<summary><strong>Can I connect more than 2 earbuds?</strong></summary>

Yes! Click **+ Add Device** to add 3, 4, or more earbuds/speakers. There's no limit.
</details>

<details>
<summary><strong>Will this work with ANY Bluetooth earbuds?</strong></summary>

Yes! Max Paire works with any brand — Sony, JBL, boAt, Samsung Galaxy Buds, AirPods (on Windows), Realme, OnePlus, Noise, and any others.
</details>

<details>
<summary><strong>Is there any delay/lag?</strong></summary>

Almost zero! Max Paire uses PortAudio C-level callbacks which run in native code (not Python). The delay is about 20-40ms which is unnoticeable.
</details>

<details>
<summary><strong>Does it use the internet?</strong></summary>

No! Max Paire is 100% offline. It doesn't connect to the internet, doesn't collect data, doesn't show ads.
</details>

<details>
<summary><strong>Windows SmartScreen shows a warning — is it safe?</strong></summary>

Yes, it's completely safe. The warning appears because the exe isn't code-signed (that costs $200/year). Just click **"More info"** → **"Run anyway"**. The entire source code is open — you can verify it yourself!
</details>

<details>
<summary><strong>My earbuds show as "Hands-Free AG Audio" — should I use that?</strong></summary>

No! That's the call/mic profile (8kHz mono = terrible quality). Always pick the **"Stereo"** or **"Headphones"** version of your earbuds.
</details>

<details>
<summary><strong>Can I use this with wired headphones too?</strong></summary>

Yes! Max Paire works with any audio output device — Bluetooth earbuds, Bluetooth speakers, wired headphones, USB audio devices, etc.
</details>

<details>
<summary><strong>Will this increase my Bluetooth range?</strong></summary>

No, Bluetooth range is a hardware limitation (usually 10 meters). But Max Paire uses large audio buffers, so brief signal drops won't cause crackling.
</details>

---

## 🛠️ Build from Source

If you want to build the exe yourself:

```bash
# 1. Clone this repo
git clone https://github.com/maheshmaximusmax/max-paire.git
cd max-paire

# 2. Install Python (if you don't have it)
# Download from https://python.org

# 3. Run the build script
BUILD.bat
# This installs dependencies and creates MaxPaire.exe in the dist/ folder

# 4. (Optional) Install as a proper Windows app
INSTALL.bat
```

### Dependencies (installed automatically by BUILD.bat)
- `pyaudiowpatch` — WASAPI audio capture
- `customtkinter` — Modern UI
- `pystray` + `Pillow` — System tray icon
- `numpy` — Audio resampling
- `pyinstaller` — EXE packaging

---

## 🤝 Contributing

Want to make Max Paire better? Feel free to:

1. Fork this repo
2. Make your changes
3. Submit a Pull Request

Ideas for contributions:
- macOS / Linux support
- Auto-reconnect when earbuds disconnect
- Volume control per device
- Audio delay adjustment for lip-sync

---

## 📄 License

MIT License — Free to use, modify, and share. See [LICENSE](LICENSE) for details.

---

## ⭐ Like it? Star this repo!

If Max Paire helped you, please give it a ⭐ star on GitHub! It helps others find this tool.

---

<p align="center">
  <strong>Made with 💜 by <a href="https://github.com/maheshmaximusmax">Max</a></strong>
</p>

<!-- SEO Keywords (for GitHub search) -->
<!-- 
connect two earbuds to one pc, connect 2 bluetooth earbuds to laptop, 
dual earbuds windows, multiple bluetooth headphones one computer,
share audio two earbuds pc, bluetooth audio splitter windows software,
mirror audio multiple devices, play sound two bluetooth speakers,
connect two bluetooth headphones windows 10 windows 11,
dual audio bluetooth pc laptop, two earbuds one laptop,
pair multiple bluetooth earbuds, audio to multiple bluetooth devices,
free bluetooth audio splitter, connect 2 wireless earbuds to pc,
share pc audio multiple earbuds, bluetooth multi device audio,
windows bluetooth dual output, play audio two headphones windows,
simultaneous bluetooth audio, multi bluetooth audio windows free
-->
