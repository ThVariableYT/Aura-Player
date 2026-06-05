<div align="center">
  <img src="https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-informational?style=flat-square&color=f472b6" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Deployment-GitHub%20Pages-blueviolet?style=flat-square" />
</div>

<br />

<div align="center">
  <h1>🎵 AuraPlayer</h1>
  <p><strong>A stunning, fully open-spurce, single-file web music player with synchronized lyrics, real-time audio visualization, and a gorgeous glassmorphism UI.</strong></p>
  <a href="https://thvariableyt.github.io/Aura-Player/">🌐 Live Demo</a> &nbsp;|&nbsp;
  <a href="#-features">✨ Features</a> &nbsp;|&nbsp;
  <a href="#-getting-started">🚀 Getting Started</a>
</div>

---

## 📸 Preview

> Drop in your audio files, pair them with `.lrc` lyric files, and experience real-time synchronized lyrics with a live audio visualizer — all in a beautiful glassmorphism interface.

---

## ✨ Features

- **🎤 Synchronized Lyrics (LRC)** — Upload `.lrc` files matching your audio file names, and AuraPlayer will auto-pair and display smooth, real-time kinetic lyrics synced to the track.
- **📊 Audio Visualizer** — A real-time circular waveform visualizer reacts to bass, mids, and trebles — the animated aurora background even pulses with the music.
- **🎨 5 Colour Themes** — Switch between beautifully curated themes that update the entire UI accent and background aurora:
  - 💜 Amethyst Aura *(default)*
  - 💚 Cosmic Emerald
  - 🔥 Sunset Ember
  - 🩵 Oceanic Sapphire
  - 🩶 Slate Monochrome
- **💿 Automatic Metadata Reading** — Tags like title, artist, album, genre, year, and embedded album art are automatically extracted from your audio files using `jsmediatags`.
- **📂 Drag & Drop Upload** — Drag and drop audio files (`.mp3`, `.wav`, `.flac`, `.ogg`, `.m4a`, `.aac`) and `.lrc` files directly into the playlist drawer. Matching filenames auto-pair lyrics.
- **🗃️ Playlist Queue** — Manage a full track queue with add, play, and remove functionality. Visual indicators show the currently active track and whether it has lyrics loaded.
- **⏭️ Playback Controls** — Play/Pause, Previous, Next, Shuffle, Repeat, and adjustable volume with mute toggle.
- **🔁 Autoplay** — Optionally enable autoplay to automatically advance to the next track when the current one finishes.
- **🖥️ Fullscreen Mode** — Expand to a true fullscreen cinematic listening experience with one click.
- **🔍 Technical Metadata Inspector** — A pop-up modal displays detailed metadata: album name, genre, release year, and file size.
- **🎵 Demo Track** — Try AuraPlayer instantly with a built-in ambient demo track (no upload needed).
- **💾 Theme Persistence** — Your chosen colour theme is saved via `localStorage` and remembered across sessions.

---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| HTML5 + CSS3 + JavaScript | Core single-file application |
| [Tailwind CSS (CDN)](https://tailwindcss.com) | Utility-first styling & responsive layout |
| [jsmediatags](https://github.com/nicktindall/jsmediatags) | ID3 / audio metadata tag reading |
| [Font Awesome 6](https://fontawesome.com) | Icons throughout the UI |
| [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) | Primary typeface |
| Web Audio API | Real-time audio analysis & visualizer |

---

## 🚀 Getting Started

AuraPlayer is a **zero-dependency, single HTML file** — no build step, no `npm install`, no server required.

### Option 1: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/ThVariableYT/Aura-Player.git
   ```
2. Open `index.html` in any modern web browser.
3. That's it — you're ready to go!

### Option 2: Use the Live Deployment
Visit the GitHub Pages deployment directly:
> **[https://thvariableyt.github.io/Aura-Player/](https://thvariableyt.github.io/Aura-Player/)**

---

## 🎵 How to Use

1. **Click the playlist icon** (folder icon or the hamburger `≡` button) to open the Audio Setlist drawer.
2. **Upload your audio files** by clicking the drop zone or dragging files in. Supported formats: `.mp3`, `.wav`, `.flac`, `.ogg`, `.m4a`, `.aac`.
3. **Add synchronized lyrics** by uploading a `.lrc` file with the **same base filename** as your audio file (e.g., `song.mp3` + `song.lrc`).
4. **Click a track** in the queue to start playback. Lyrics will auto-sync in the main view.
5. **Click any lyric line** to jump directly to that timestamp in the track.
6. **Use the Themes button** in the header to switch colour themes at any time.
7. **Click the ℹ️ icon** on the track info pill to open the Technical Metadata Inspector.
8. **Try the Demo** by clicking the `Try Demo Track` button — no files needed!

---

## 📁 Repository Structure

```
Aura-Player/
├── index.html       # The entire application (HTML + CSS + JS)
├── README.md        # Project documentation
└── .gitattributes   # Git line-ending configuration
```

---

## 🔮 Roadmap / Planned Features

- [ ] Equalizer controls
- [ ] Sleep timer
- [ ] Keyboard shortcut support
- [ ] Export / share playlist

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/ThVariableYT">ThVariableYT</a>
</div>
