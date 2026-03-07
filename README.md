# Kams Bot

A local AI assistant that runs entirely on your Mac. No cloud, no subscriptions, no internet required after setup. Your conversations stay private on your device.

## Features

- Fully offline after first setup
- Powered by Ollama and Qwen 2.5
- Streams responses in real time
- Lightweight and fast

## Requirements

- macOS 13 or later
- [Ollama](https://ollama.com/download) installed

## Installation

1. Install Ollama from [ollama.com/download](https://ollama.com/download)
2. Download `KamsBot.dmg` from the [latest release](https://github.com/kichhu-rishu/kams-bot/releases/latest)
3. Open the DMG and drag **Kams Bot** into your Applications folder
4. Right-click `Kams Bot.app` -> **Open** (required the first time since the app is not notarized)
5. On first launch, the app will automatically download the AI model (~1 GB) -- this only happens once
6. Once the download is complete, you can turn off your internet and use it fully offline

**If you see "Apple could not verify" or "unidentified developer":** Right-click the app -> Open -> Open. This is a one-time step.

**Or run this in Terminal to bypass Gatekeeper:**
```
xattr -cr /Applications/"Kams Bot.app"
```

## Usage

Just type your question and press Enter. The AI responds directly on your device -- nothing is sent to any server.
