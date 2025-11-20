# COMMS LINK

Browser-based P2P voice/text communication app.

## Quick Start (Recommended)

**Best way to avoid microphone permission prompts:**

### Option 1: Python HTTP Server
```bash
cd h:/Development/AIMMO
python -m http.server 8000
```
Then open: http://localhost:8000/index.html

### Option 2: Just Open in Chrome
Double-click `index.html` - it works but Chrome will ask for mic permission frequently.

## How to Use

1. Open `index.html` in Chrome or Edge
2. Share your Peer ID with friends  
3. Enter their ID and click JOIN
4. Click "START MIC" to enable voice
5. Speak - your words are transcribed and sent

## Features

- Multi-user P2P connections
- Voice input (speech-to-text)
- Voice avatars (Male/Female/Robot)
- Text chat mode
- Works across the internet

## Note

The `dist/COMMS_LINK.exe` Electron build has microphone issues. Use the browser version instead.
