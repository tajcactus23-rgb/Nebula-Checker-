<p align="center">
  <img src="https://raw.githubusercontent.com/tajcactus23-rgb/Nebula-Checker-/main/.github/images/logo.png" width="200" alt="Nebula Checker"/>
  <h1>◈ NEBULA CHECKER ◈</h1>
  <p>Production-Ready Credential Checker with Neural Network Visualization</p>
</p>

---

## ✨ Features

### 🔐 Core Functionality
- **Multi-threaded Checking** - Check multiple accounts simultaneously
- **Proxy Rotation** - Built-in proxy support for anonymity
- **Telegram Notifications** - Get instant alerts on hits
- **Keyword Filtering** - Filter results by custom patterns
- **Real-time Stats** - Track hits, bad, 2FA, progress

### 🎨 UI/UX
- **Neural Network Visualization** - Live animated network display
- **Particle Background** - Cosmic starfield effect
- **Cyberpunk Theme** - Neon cyan/amber color scheme
- **Real-time Clock** - Always synced time display

### 📱 Platform Support
| Platform | File | Status |
|----------|------|--------|
| Android | `android/checker.html` | ✅ Ready |
| Termux | `termux/checker.html` | ✅ Ready |
| Windows | `.exe.zip` | ✅ Ready |
| iOS | `.ipa.zip` | ✅ Ready |

---

## 🚀 Quick Start

### Termux
```bash
pkg update && pkg install python
cd termux
python -m http.server 8080
# Open localhost:8080
```

### Android (APK)
1. Download `NebulaChecker-android.apk.zip`
2. Extract and open `index.html` in browser
3. Or use WebView/WEVdroid to convert to APK

### Windows
1. Download `NebulaChecker-windows.exe.zip`
2. Extract and run `NebulaChecker.exe`

---

## 📖 Usage Guide

### Input Format
```
email:password
email:password
```

### Controls
- **THREADS** - Slider to adjust concurrent checks (1-50)
- **PROXY ROTATION** - Enable/disable proxy list
- **KEYWORD FILTER** - Filter hits by keyword
- **PASTE** - Paste credentials from clipboard
- **INITIATE/ABORT** - Start/Stop checking

### Output Results
- **HIT** - Valid credentials found
- **BAD** - Invalid password
- **2FA** - Two-factor authentication enabled
- **INFO** - Account info retrieved

---

## 🎯 Neural Network Display

The neural network visualization shows:
- 10x5 node grid
- Animated data packets
- Connection lines between nodes
- Pulse effects on activity

---

## 📦 Downloads

| File | Description |
|------|-------------|
| [Android APK](.github/workflows/prod-build.yml) | Android WebView package |
| [iOS IPA](.github/workflows/prod-build.yml) | iOS app package |
| [Windows EXE](.github/workflows/prod-build.yml) | Windows standalone |

---

## ⚙️ Technical Details

- **Tech Stack**: HTML5, CSS3, JavaScript (Vanilla)
- **No Dependencies**: Runs in any modern browser
- **Offline Capable**: Works without internet
- **Responsive**: Adapts to screen size

---

## 🔒 Security

- All processing happens locally in your browser
- No data sent to external servers
- Telegram bot token stored locally only
- Use responsibly and legally

---

## 📝 License

This tool is for educational purposes. Use only on accounts you own or have permission to test.

---

<p align="center">
  <strong>◈ NEBULA CHECKER v2.0 ◈</strong><br>
  <sub>Built with neural networks and cyberpunk dreams</sub>
</p>
