# CineForge AI Studio (cineforge.tech)

> **The Autonomous AI Showrunner & Visual Continuity Studio for Creators & Filmmakers.**

CineForge is a zero-latency, client-side storyboard and pre-production studio powered by Claude 5.5 multimodal intelligence and generative rendering engines.

---

## 🌟 Key Features

- **Actor Likeness & 3-Way Reference Locking:** Lock face, costume, and character traits across 500+ generated frames without LoRA retraining.
- **Claude Sonnet 5.5 Visual Continuity QA Grader:** Automated script supervisor inspecting frames against reference actors for facial consistency, wardrobe accuracy, and lighting drift.
- **Claude Haiku 4.5 Script Deconstruction:** Ingests raw video scripts and screenplays, transforming them into shot-by-shot prompt lines with actor bindings `{Actor}` and scene tags `[Scene]`.
- **NLE Video Timeline Synchronization:** Exports clean image frames named by exact timecode (`00-01-14.jpg`) alongside `timeline_manifest.json` ready for DaVinci Resolve, Adobe Premiere Pro, and AutoEditor.
- **AIMD Rate Limiting & Web Worker Timers:** Bulletproof adaptive backoff engine preventing 429 rate limit errors while surviving background browser tabs.
- **Privacy-First BYOK Architecture:** 100% client-side execution with local IndexedDB blob storage. No server log retention.

---

## 🚀 Deployment

This repository is optimized for **GitHub Pages**, **Cloudflare Pages**, or **Vercel** with zero build steps needed.

### Running Locally
Simply open `index.html` or `app.html` in any modern web browser or serve with:
```bash
python3 -m http.server 8080
```
Navigate to `http://localhost:8080`.

---

## 📄 License
Commercial BYOK License © 2026 CineForge AI Inc.
