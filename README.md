# Autonomyx Music Player

AI-powered music player skill for the Autonomyx / AgentNXXT platform.

## Features

| Tab | Description | Tokens? |
|---|---|---|
| **Upload & Play** | Local audio files with oscilloscope waveform visualizer | ❌ None |
| **Stream URL** | Direct mp3/ogg/wav URL streaming with waveform | ❌ None |
| **Mood Playlist** | Describe a vibe → AI-curated 10-track playlist with YouTube + SoundCloud links | ✅ Per generate |
| **Search & Play** | Search by track/artist → YouTube iframe embed | ✅ Per search |

## Stack

- Web Audio API (`AnalyserNode`) for oscilloscope waveform
- Anthropic Claude API (`claude-sonnet-4-20250514`) for Mood Playlist and Search
- Pure HTML/CSS/JS — no framework, no build step

## Branding

- **Colors**: Autonomyx Blue `#1B5EBE`, Deep Navy `#001141`, Electric Cyan `#00CFFF`
- **Font**: IBM Plex Sans / IBM Plex Mono
- **Tagline**: From Foundational To Frontier: FullStack AI

## Files

| File | Description |
|---|---|
| `player.html` | Standalone deployable player — open in any browser |
| `SKILL.md` | AgentNXXT skill definition |
| `autonomyx-music-player.skill` | Packaged skill for AgentNXXT marketplace installation |

## Usage

Open `player.html` directly in a browser, or embed it in any web page via iframe.

The Mood Playlist and Search tabs require an Anthropic API key available in the execution context (provided automatically on Claude.ai).

---

**Autonomyx** · [openautonomyx.com](https://openautonomyx.com) · [AgentNXXT Marketplace](https://agentnxxt.github.io/agentskills)
