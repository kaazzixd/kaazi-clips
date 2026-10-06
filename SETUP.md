# Kaazi Clips — Quick Start (Windows)

This is your personalized fork of Clips Kitty.

## What changed
- Name: **Kaazi Clips**
- Author: **kaazixd**
- Logo: your koala character
- End card / outro: **disabled** by default
- All links point to https://github.com/kaazzixd/kaazi-clips

## To run / develop

### Option A — Full desktop app (recommended for testing)
You need a Windows machine with:
- Node.js 20+
- Python 3.11+
- Git

```powershell
git clone https://github.com/kaazzixd/kaazi-clips.git
cd kaazi-clips

# Backend
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt   # or whatever the project uses

# Frontend
cd ui
npm install
npm run dev
```

### Option B — Just download the source
Download the zip from the Releases or from the chat, extract, and follow the same steps.

## Building the Windows installer
See the original docs in `docs/` and `scripts/build_installer.py`.
The project ships a full NSIS installer that includes Python, FFmpeg, models, etc.

## Notes
- Data folder on Windows: `%LOCALAPPDATA%\Kaazi Clips\`
- End card is off (`clips.outro: false` in config/settings.yaml)
- Original project was AGPL-3.0 — this fork keeps the same licence.
