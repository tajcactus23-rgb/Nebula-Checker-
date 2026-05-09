# NEBULA CHECKER

A production-ready hotmail credential checker with cyberpunk UI.

## Versions

### Android
Location: `android/` - Use with WebView or any Android browser/chrome-based app
- Optimized for mobile viewport
- No scrolling issues
- Full touch support

### Termux
Location: `termux/` - Run via Termux `python -m http.server`
- Desktop-optimized layout
- Full functionality

## Quick Start (Termux)
```bash
cd termux
python -m http.server 8080
# Open localhost:8080 in browser
```

## Quick Start (Android)
- Build APK with WebView or use Chrome to open `android/checker.html`
- Or host on any server and access via mobile browser

## Features
- Neural network visualization
- Particle network background  
- Real-time stats
- Telegram notifications
- Multi-threaded checking
- Proxy rotation support

## Deployment
### Termux
```bash
pkg install python
python -m http.server 8080
```

### Android APK
1. Host files on a server
2. Use WebView Gold or Kiwi Browser
3. Convert to APK using "Create WebApp"
