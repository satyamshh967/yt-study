# yt-study 📺📝

> **Smart Browser Extension for Video Transcription & Interactive Note-Taking.**

[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-Build_Tool-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev/)
[![WebExtension](https://img.shields.io/badge/Chrome_Extension-Manifest_v3-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://developer.chrome.com/docs/extensions/)

---

## 📖 Overview

`yt-study` is a browser extension engineered to turn YouTube into an active technical learning workstation. It integrates directly with video players to capture timestamps, provide live transcript lookups, and allow developers to take structured, timestamped markdown notes without losing focus.

---

## ✨ Features

- **⏱️ Timestamp Synchronization:** Single-click capture of current video playback timestamp linked directly to your notes.
- **🎙️ Transcription Service:** Integrated transcription pipeline (`transcriber/`) for generating and searching video transcripts locally.
- **📝 Structured Note Taking:** Clean markdown-supported editor with syntax highlighting for code snippets.
- **⚡ Manifest V3 Compatible:** Built according to the latest modern Chrome Extension standards for speed, security, and battery efficiency.

---

## 🚀 Getting Started

### Prerequisites
- **Node.js (v18+)** & **npm**

### Build the Extension
```bash
# Clone repository
git clone https://github.com/satyamshh967/yt-study.git
cd yt-study

# Install packages
npm install

# Build extension bundle
npm run build
```

### Load in Google Chrome
1. Navigate to `chrome://extensions/` in your browser.
2. Toggle on **Developer mode** in the top right.
3. Click **Load unpacked** and select the generated `dist/` directory.
4. Open any YouTube video and enjoy enhanced study sessions!

---

## 👤 Author
- **Satyam Sharma** - [@satyamshh967](https://github.com/satyamshh967)
