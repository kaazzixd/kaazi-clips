# Kaazi Clips — Quick Start (Windows)

## What this is
Kaazi Clips is a local AI video clipper for Windows.

## Requirements for development
- Node.js 20+
- Python 3.11+
- Git

## Run in development

```powershell
git clone https://github.com/kaazzixd/kaazi-clips.git
cd kaazi-clips

# Backend
python -m venv .venv
.venv\Scripts\activate
# Install Python dependencies (see requirements / project docs)

# Frontend
cd ui
npm install
npm run dev
```

## Notes
- Data folder on Windows: `%LOCALAPPDATA%\Kaazi Clips\`
- End card is disabled by default (`clips.outro: false`)
- Licence: AGPL-3.0
