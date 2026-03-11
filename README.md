<p align="center">
  <img src="https://raw.githubusercontent.com/RALIST/writer-studio-releases/master/assets/appicon.png" width="128" alt="Writer Studio">
</p>

<h1 align="center">Writer Studio</h1>

<p align="center">
  <strong>The writing tool that never forgets your story</strong><br>
  A native desktop app for fiction authors — professional writing environment with an AI assistant that understands your entire manuscript.
</p>

<p align="center">
  <a href="https://github.com/RALIST/writer-studio-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/RALIST/writer-studio-releases?style=flat-square&label=Latest%20Release&color=4a90d9" alt="Latest Release">
  </a>
  <img src="https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-blue?style=flat-square" alt="Platforms">
  <img src="https://img.shields.io/badge/local--first-no%20cloud%20required-green?style=flat-square" alt="Local First">
  <img src="https://img.shields.io/badge/license-proprietary-lightgrey?style=flat-square" alt="License">
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.ru.md">🇷🇺 Русский</a>
</p>

---

## Download

| Platform | Download | Notes |
|----------|----------|-------|
| **macOS** | [Universal (.tar.gz)](https://github.com/RALIST/writer-studio-releases/releases/latest) | Apple Silicon & Intel, macOS 11+ |
| **Windows** | [Installer (.exe)](https://github.com/RALIST/writer-studio-releases/releases/latest) | 64-bit, Windows 10+ |
| **Linux** | [AppImage](https://github.com/RALIST/writer-studio-releases/releases/latest) · [.deb](https://github.com/RALIST/writer-studio-releases/releases/latest) | 64-bit, Ubuntu 20.04+ |

> All releases include SHA256 checksums for verification.

---

## What is Writer Studio?

Writer Studio is a **local-first** desktop application built for fiction writers who want a single, focused environment for organizing, writing, and polishing their manuscripts — with an AI assistant that has full context of your story.

No subscriptions. No cloud lock-in. Your files stay on your disk in an open JSON format you can always read and move.

### Why not just use ChatGPT / Scrivener / Word?

| Need | Common workaround | Writer Studio |
|------|-------------------|---------------|
| Organize chapters & scenes | Scrivener, Notion | Built-in hierarchical structure |
| AI help that knows your book | Paste context manually into ChatGPT | AI reads your entire manuscript automatically |
| Grammar & style check for fiction | Grammarly (generic, not fiction-aware) | Native proofreader tuned for literary prose |
| Export to EPUB / DOCX | Vellum, Calibre | One-click export with validation |
| Character & world tracking | Separate spreadsheet or wiki | Character cards + relationship graphs |

---

## Features

### ✍️ Writing & Editing

- Rich text editor (TipTap) with formatting, focus and zen modes
- Distraction-free writing with typewriter scrolling and paragraph focus
- Real-time word count, reading time, and session statistics
- Split-view and multi-pane layout (up to 4 panes, freely nestable)
- Multiple themes: Dark, Light, Sepia, Night Owl, Focus, High Contrast, and Auto (follows system)

### 📖 Book Structure

- Hierarchical organization: **Book → Acts → Chapters → Scenes**
- Drag-and-drop reordering with status indicators (*draft / revised / final*)
- Scene metadata: POV, date/time, tags, location
- Book-level composite editor for full-manuscript overview
- Front matter and back matter support

### 👤 Characters & World

- Character cards with appearance, personality, motivations, and relationships
- Structural character models (Egri 3D, Weiland arcs)
- Visual relationship graphs
- Cross-book character profiles for series writers

### 🤖 AI Assistant

- **Full manuscript context** — the AI sees your entire book, characters, notes, and metadata
- **Book Guide (BOOK.md)** — per-book author instructions that shape the AI's behavior
- **Natural language commands:** *"Split this scene into 3 parts"*, *"Create character cards from this chapter"*, *"What are the continuity issues in Act 2?"*
- **Multiple AI providers:** Claude (Anthropic), GPT (OpenAI), Ollama (local/offline models)
- **Bring-your-own-key** — no middleman, your API key goes directly to the provider
- **Approval workflow** — you confirm before the AI takes any structural action
- **AI Autocomplete** — ghost-text suggestions while you write, non-intrusive
- **AI Scene Review** — editorial feedback with full book context

### 🔍 Proofreading

- Native grammar and style checker built for fiction (not generic business text)
- Spell checking with correction suggestions
- POS-aware rules that understand dialogue, narrative, and literary constructs
- Inline highlighting with one-click correction

### 📊 Writing Statistics

- Daily word goal with progress bar and streak counter
- Session timer — tracks active writing time per sitting
- Weekly overview with per-day word counts
- Book-level totals: total words, estimated reading time

### 🔎 Navigation

- **Quick Jump** (`Cmd/Ctrl+P`) — instant fuzzy search across your entire book
- **Command Palette** (`Cmd/Ctrl+Shift+P`) — IDE-style access to all actions
- Full-text and regex search across all scenes

### 📦 Import & Export

| Format | Import | Export |
|--------|--------|--------|
| EPUB 3.0 | ✓ (PRO) | ✓ — with KDP/Kobo/Apple Books validation |
| DOCX | ✓ (PRO) | ✓ |
| Scrivener | ✓ (PRO) | — |
| Markdown | ✓ | ✓ |
| TXT | ✓ | ✓ |
| PDF | — | ✓ |
| HTML | — | ✓ |

### 🔒 Data Safety

- Auto-save every 30 seconds with crash recovery
- **Scene snapshots** — lightweight manual checkpoints before experimenting with a scene
- Automatic hourly backups with configurable retention
- **Open storage format** — plain JSON files, no vendor lock-in
- Git-based version history for your manuscript

### 🌐 Localization

- English and Russian interfaces

---

## Installation

### macOS

1. Download the `.tar.gz` from the [latest release](https://github.com/RALIST/writer-studio-releases/releases/latest)
2. Extract it and drag **Writer Studio** to your Applications folder
3. On first launch: right-click → **Open**, or go to **System Settings → Privacy & Security** and click **Open Anyway**

### Windows

1. Download the `.exe` installer from the [latest release](https://github.com/RALIST/writer-studio-releases/releases/latest)
2. Run the installer — if you see a SmartScreen warning, click **More info → Run anyway**

### Linux

**AppImage:**
```bash
chmod +x Writer-Studio-*.AppImage
./Writer-Studio-*.AppImage
```

**Debian/Ubuntu:**
```bash
sudo dpkg -i writer-studio_*.deb
```

---

## Auto-Update

Writer Studio includes a built-in auto-updater. You'll be notified in-app when a new version is available and can update with one click — no need to revisit this page.

---

## System Requirements

| Platform | Minimum |
|----------|---------|
| macOS | 11 (Big Sur) or later |
| Windows | 10 (64-bit) or later |
| Linux | Ubuntu 20.04+, Fedora 36+, or equivalent |

---

## Privacy & AI Keys

Writer Studio is **local-first by design**:

- All your writing is stored on your machine — no account required, no sync to any server
- AI features are **optional** — the app is fully usable without any AI key
- When you use AI, your API key is sent directly to your chosen provider (Anthropic, OpenAI, or your local Ollama instance) — Writer Studio never sees it
- Telemetry (crash reports) is opt-in and can be disabled at any time in Settings

---

## Feedback & Issues

Found a bug or have a suggestion? [Open an issue](https://github.com/RALIST/writer-studio-releases/issues) in this repository.

---

<p align="center">
  <sub>Built with Go, Svelte, and Wails · Local-first · Made for writers</sub>
</p>
