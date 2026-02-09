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
    <img src="https://img.shields.io/github/v/release/RALIST/writer-studio-releases?style=flat-square&label=Latest%20Release" alt="Latest Release">
  </a>
  <img src="https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-blue?style=flat-square" alt="Platforms">
  <img src="https://img.shields.io/badge/license-proprietary-lightgrey?style=flat-square" alt="License">
</p>

---

## Download

| Platform | Download | Notes |
|----------|----------|-------|
| **macOS** | [Universal (.tar.gz)](https://github.com/RALIST/writer-studio-releases/releases/latest) | Apple Silicon & Intel |
| **Windows** | [Installer (.exe)](https://github.com/RALIST/writer-studio-releases/releases/latest) | 64-bit |
| **Linux** | [AppImage](https://github.com/RALIST/writer-studio-releases/releases/latest) / [.deb](https://github.com/RALIST/writer-studio-releases/releases/latest) | 64-bit |

> All releases include SHA256 checksums for verification.

## What is Writer Studio?

Writer Studio is a local-first desktop application built for fiction writers who want a single tool for organizing, writing, and exporting their manuscripts — with an AI agent that has full context of your story.

It replaces the need to juggle multiple apps (Scrivener for structure, separate AI chat for brainstorming, Vellum for export) by combining everything into one cohesive environment.

## Key Features

### Writing & Editing
- Rich text and plain text editing modes
- Distraction-free writing with focus and zen modes
- Real-time word count, reading time, and session tracking
- Typewriter scrolling, paragraph focus, split view

### Book Structure
- Hierarchical organization: Book → Acts → Chapters → Scenes
- Drag-and-drop reordering with status indicators (draft / revised / final)
- Scene metadata: POV, date/time, tags, location
- Front and back matter support

### Characters & World
- Character cards with appearance, personality, relationships
- Structured character models (Egri 3D, Weiland arcs)
- Visual relationship graphs
- Cross-book character profiles for series writers

### AI Assistant
- Full manuscript context — the AI sees your entire book, characters, and metadata
- Natural language commands: *"Split this scene into 3 parts"*, *"Create character cards from this chapter"*
- Multiple providers: Claude (Anthropic), GPT (OpenAI), Ollama (local models)
- Bring-your-own-key option for privacy-focused users
- Approval workflow — you confirm before the AI takes structural actions

### Navigation
- Quick Jump (`Cmd/Ctrl+P`) for instant fuzzy search
- Command Palette (`Cmd/Ctrl+Shift+P`) for IDE-style access to all actions
- Full-text and regex search across the entire book

### Import & Export
- **Import:** TXT, Markdown (free) · DOCX, Scrivener, EPUB (PRO)
- **Export:** EPUB 3.0, DOCX, Markdown, TXT, PDF, HTML
- Export validation for KDP, Kobo, and Apple Books

### Data Safety
- Auto-save every 30 seconds with crash recovery
- Automatic hourly backups with configurable retention
- JSON-based open storage format — no vendor lock-in
- Git-based version history

### Localization
- English and Russian interfaces

## Installation

**macOS:** Download the `.tar.gz`, extract, and drag Writer Studio to Applications.
On first launch, right-click → Open (or allow in System Settings → Privacy & Security).

**Windows:** Download and run the installer (`.exe`). You may see a SmartScreen warning — click "More info" → "Run anyway".

**Linux:** Download the AppImage, make it executable (`chmod +x Writer-Studio-*.AppImage`), and run. Alternatively, install the `.deb` package.

## Auto-Update

Writer Studio includes a built-in auto-updater. Once installed, you'll be notified when new versions are available.

## System Requirements

- **macOS** 11+ (Big Sur or later)
- **Windows** 10+ (64-bit)
- **Linux** — modern 64-bit distribution (Ubuntu 20.04+, Fedora 36+, etc.)

## Feedback & Issues

Found a bug or have a suggestion? Open an issue in this repository.

---

<p align="center">
  <sub>Built with Go, Svelte, and Wails</sub>
</p>
