# Kams Bot

A local AI assistant that runs entirely on your Mac. No cloud, no subscriptions, no internet required after setup. Your conversations stay private on your device.

## Features

- Fully offline after first setup
- Powered by Qwen 2.5 (runs locally, no Ollama install needed)
- Streams responses in real time
- Lightweight and fast

## Requirements

- macOS 13 or later

## Installation

1. Download `KamsBot.dmg` from the [latest release](https://github.com/kichhu-rishu/kams-bot/releases/latest)
2. Open the DMG and drag **Kams Bot** into your Applications folder
3. Right-click `KamsBot.app` -> **Open** (required the first time since the app is not notarized)
4. On first launch, the app will automatically download the AI model (~1 GB) -- this only happens once
5. Once the download is complete, you can use it fully offline

**If you see "unidentified developer": Run this in Terminal:
```
xattr -cr /Applications/KamsBot.app
```

## Usage

Just type your question and press Enter. The AI responds directly on your device -- nothing is sent to any server.
