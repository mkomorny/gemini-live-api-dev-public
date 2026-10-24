# Gemini Live API Development

> **Tri-Platform Agent Skill** for Claude Desktop / Code, Grok CLI, and Google Antigravity / Gemini.  
> Real-time, bidirectional streaming with Gemini 3.8 Live over WebSockets for audio, video, and text.

---

## Overview

`gemini-live-api-dev` provides standardized capabilities across conversational AI platforms:
- Bidirectional WebSocket streaming architecture for low-latency audio, video, and text.\n- Voice activity detection (VAD) configuration and barge-in interruption handling.\n- Extended thinking support (gemini-3.8-live-extended-thinking) and background reasoning.\n- Asynchronous function calling and live audio transcription streaming.\n- Tri-platform NTFS junctions connecting Claude, Grok, and Antigravity.

---

## Tri-Platform Architecture

Zero duplicate code across platforms. Canonical source resides in `.agents`:
- **Canonical Source**: `C:\Users\<you>\.agents\skills\gemini-live-api-dev`
- **Claude**: `C:\Users\<you>\.claude\skills\gemini-live-api-dev` (NTFS Junction)
- **Grok**: `C:\Users\<you>\.grok\skills\gemini-live-api-dev` (NTFS Junction)
- **Antigravity**: `C:\Users\<you>\.gemini\config\skills\gemini-live-api-dev` (NTFS Junction)

---

## Documentation Suite

- [`HOW_TO_USE.txt`](HOW_TO_USE.txt): Standardized user guide and prompt templates.
- [`IMPLEMENTATION_PLAN.md`](IMPLEMENTATION_PLAN.md): Feature checklist and roadmap.
- [`App Changes Tracker.html`](App%20Changes%20Tracker.html): Interactive visual version log.
- [`SKILL.md`](SKILL.md): Agent system instructions and triggers.
