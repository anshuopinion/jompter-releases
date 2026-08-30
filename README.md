# Jompter for macOS — Releases

**Stop typing prompts. Speak them.**

Jompter turns **voice, screenshots and screen recordings** into one clean,
AI-ready prompt for your coding assistant — Claude Code, Cursor, Claude.ai and
the rest. Speech, language models and speech synthesis can all run **on your
Mac**, offline.

**Latest release: 0.2.2** · [see all releases](https://github.com/anshuopinion/jompter-releases/releases)

## What it does

- **Dictate anywhere** — hold a key in any app, talk, let go. The text lands where you were typing.
- **Snap & annotate** — grab a screen region, mark it up, and drop it into the prompt.
- **Video Prompt** *(beta)* — record a region; Jompter samples the frames, drops the near-duplicates, transcribes the audio and compiles a repro.
- **Board** *(beta)* — a whiteboard you can draw on, or hand to an AI agent over a local MCP connection.
- **Speak** — have any selected text read aloud, optionally explained or translated.
- **Jompter Remote** — see and control your Mac from your iPhone.

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

## Requirements

- **Apple Silicon only.** Intel Macs are not supported — the on-device AI models
  don't ship for Intel, and Apple has sunset the platform.
- **macOS 13 Ventura or later.**
- Signed and notarized by Apple.

## Install

1. Open the `.dmg` and drag **Jompter** into **Applications**.
2. Launch it and work through the setup steps.
3. Grant the macOS permissions it asks for — there are **four**, and each one
   gates specific features:

   | Permission | Needed for |
   |---|---|
   | Microphone | Recording your voice |
   | Accessibility | Typing dictated text, global hotkeys, reading your selection |
   | Screen Recording | Screenshots, screen recordings, Remote |
   | **Remote input** | Actually sending keystrokes and clicks |

   Accessibility and **Remote input** are *separate* permissions that live in the
   same System Settings pane. Granting only the first is the most common reason
   dictation appears to do nothing.

Two things that surprise people on day one: **closing the window doesn't quit
Jompter** (it hides — press <kbd>⌘</kbd><kbd>⇧</kbd><kbd>J</kbd> to bring it
back), and the app posts **no notifications**, so nothing tells you a
transcription or a model download has finished.

## Documentation

Full user manual, with screenshots: **https://jompter.com/docs**

- [Install and first run](https://jompter.com/docs/getting-started/install)
- [Permissions](https://jompter.com/docs/getting-started/permissions) — the step people get stuck on
- [Plans and access](https://jompter.com/docs/getting-started/plans)
- [Troubleshooting](https://jompter.com/docs/reference/troubleshooting)

## Jompter Remote for iPhone

Control your Mac from your phone. It is in **open beta on TestFlight**, not on
the App Store yet:

**[Join the beta](https://testflight.apple.com/join/e1EPnYN4)** · [docs](https://jompter.com/docs/phone)

Remote needs a cloud subscription, an active trial or a beta grant — a one-time
licence does not include it.

## Links

- Website: https://jompter.com
- Documentation: https://jompter.com/docs
- Pricing: https://jompter.com/pricing
- Founding beta (free seats): https://jompter.com/beta
- Support: https://jompter.com/support

## Note

This repository hosts **release binaries only**; the source is private. For bugs
and feature requests, see https://jompter.com/support.
