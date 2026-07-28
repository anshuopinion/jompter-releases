# Jompter for macOS — Releases

**Stop typing prompts. Speak them.**

Jompter is a macOS app that turns **voice dictation, screenshots, and screen
recordings** into one clean, AI-ready context bundle for your AI coding
assistant — Claude Code, Cursor, Claude.ai, and more.

- **Voice → prompt**: dictate naturally; on-device Whisper transcribes it locally.
- **Screenshot/record → context**: capture what you're looking at and attach it to your prompt.
- **Local-first & private**: transcription happens on your Mac, not in the cloud.

## Download

**Homebrew** (easiest):

```sh
brew install --cask anshuopinion/jompter/jompter
```

Or grab the latest `.dmg` from
[**Releases → Latest**](https://github.com/anshuopinion/jompter-releases/releases/latest),
or from **https://jompter.com**.

| Asset | Mac |
|---|---|
| `Jompter_*_aarch64.dmg` | Apple Silicon (M1/M2/M3/M4) |

**Apple Silicon only.** Intel Macs are not supported — Jompter's on-device AI
models don't ship for Intel, and Apple has sunset the platform. Requires an
M-series Mac on macOS Big Sur or later. The app is signed and notarized by Apple.

## Install

1. Open the `.dmg`.
2. Drag **Jompter** into **Applications**.
3. Launch it — on first run, grant microphone and screen-recording permissions
   when macOS asks (Jompter needs them to capture your voice and screen).

## Links

- Website: https://jompter.com
- Founding beta (free seats): https://jompter.com/beta
- Windows waitlist: https://jompter.com (shown automatically to Windows visitors)

## Note

This repository hosts **release binaries only**. The source code is private.
For bugs and feature requests, email support via https://jompter.com.
