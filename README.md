# TextForge ✦
# LINK : https://claude.ai/public/artifacts/be40e390-ce38-44e4-9e8c-109b95d7e83c

> An all-in-one AI writing cleanup suite — detect, remove, rewrite, and paraphrase.

---

## What is TextForge?

TextForge is a single-file, browser-based AI writing tool with 4 core modules. Paste your text, pick a tool, and get clean, original, human-sounding output.

---

## Tools

| Tool | What it does |
|------|-------------|
| ✦ **Plagiarism Remover** | Rewrites text so it's 100% original — no traceable phrases, no matching structure. Built to pass Turnitin, Copyscape, and similar checkers. |
| ⌁ **AI Tag Remover** | Converts AI-generated content into natural human writing. Strips robotic patterns and injects personality. Bypasses GPTZero, Originality.ai, Copyleaks, and Winston AI. |
| ◈ **Paraphraser** | Rephrases text in 5 modes — Standard, Simplify, Creative, Academic, Fluent — with zero phrasing match to the original. |
| ⬡ **AI Checker** | Scores text 0–100% for AI probability. Returns a full report: verdict, suspicious phrases, burstiness, perplexity, passive voice, and sentence uniformity. |

---

## Features

- 🔥 Single HTML file — no build step, no dependencies, no install
- 🎛️ Per-tool option chips to customize output tone, length, and style
- 📊 Live word count and quality stats after every run
- 📋 One-click copy for all outputs
- 🌑 Dark industrial UI with noise texture and accent colors
- 📱 Responsive — works on desktop and mobile

---

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/textforge.git
cd textforge
```

### 2. Open in browser

```bash
open ai-text-cleaner.html
```

No server needed. Just open the file directly in any modern browser.

---

## Project Structure

```
textforge/
│
├── ai-text-cleaner.html   # Entire app — HTML + CSS + JS in one file
└── README.md
```

---

## How It Works

Each tool uses a specialized prompt engineered for that task:

- **Plagiarism Remover** — Structural transformation rules, vocabulary replacement targets, and a built-in Turnitin mental check.
- **AI Tag Remover** — Targets every known AI fingerprint pattern and injects human signals: burstiness, contractions, directness, and varied rhythm.
- **Paraphraser** — Targets 0% match with the original while maintaining 100% meaning retention.
- **AI Checker** — Returns a structured JSON report with probability score, verdict, key signals, and suspicious phrase extraction.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML, CSS, JavaScript |
| Fonts | Syne + Space Mono (Google Fonts) |
| Hosting | Any static host (Vercel, Netlify, GitHub Pages) |

---

## Deployment

TextForge is a static file — deploy it anywhere:

```bash
# Netlify
netlify deploy --dir .

# Vercel
vercel .

# GitHub Pages
# Push to repo → Settings → Pages → Deploy from branch
```

---

## Roadmap

- [ ] Grammar Fixer
- [ ] Tone Changer
- [ ] Summarizer
- [ ] Word Expander
- [ ] History / saved sessions
- [ ] Export as PDF or DOCX

---

## License

MIT — free to use, modify, and distribute.
