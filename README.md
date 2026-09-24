# ✦ Aurora — Free Music Synthesizer & Player

Aurora is a zero-dependency, lightweight web audio player and live algorithmic music generator built for short-form content creators (Reels, TikTok, and YouTube Shorts)[cite: 1]. It synthesizes full ambient, lo-fi, synthwave, drill, phonk, and pop tracks directly inside your browser using the native Web Audio API—complete with offline WAV rendering, custom audio uploads, and a reactive audio visualizer[cite: 1].

---

## ✨ Features

- **Live In-Browser Synthesis**: Generates dynamic chord progressions, basslines, arpeggios, and multi-genre drum patterns directly in real-time using native `AudioContext` oscillators, noise buffers, and filters[cite: 1].
- **Creator-Ready Clip Lengths**: Seamlessly preview clips tailored for social media: 15s, 30s, 60s, or full length[cite: 1].
- **Instant WAV Export**: Renders procedural audio to 16-bit PCM `.wav` files via an `OfflineAudioContext` for instant download with zero server latency[cite: 1].
- **Audio File Upload & Drag-and-Drop**: Drop your own audio files (`.mp3`, `.wav`, `.m4a`, `.ogg`, `.flac`) directly into the window to play them through the visualizer[cite: 1].
- **Real-Time Visualizer**: Dynamic HTML5 `<canvas>` frequency visualizer that adapts to the theme of the current track[cite: 1].
- **Dynamic Theming**: Custom background gradient blobs and colors that morph to match each track's unique palette, paired with light/dark theme toggling[cite: 1].
- **Instant Search & Filter**: Filter tracks by mood, genre tags, and contextual search (e.g., "dance", "vlog", "gym", "chill")[cite: 1].

---

## 🎵 Included Procedural Tracks

Aurora includes built-in procedural tracks across various genres and use cases[cite: 1]:

| Track | Artist | Genre / Mood | Best For |
| :--- | :--- | :--- | :--- |
| **Main Character** | Kai Ora | Viral / Dance (128 BPM) | Dance trends[cite: 1] |
| **Glow Up** | Sunday Static | Hype / Dance (124 BPM) | Transitions & glow-ups[cite: 1] |
| **Night Drift** | Kai Ora | Phonk (132 BPM) | Car & attitude edits[cite: 1] |
| **Trap Season** | Rehan & Co | Trap (140 BPM) | Gym & sports edits[cite: 1] |
| **Midnight Rain** | Luna Vale | Lo-fi (76 BPM) | Study & relaxed b-roll[cite: 1] |
| **Weekend Mode** | Sunday Static | Pop / Vlog (100 BPM) | Travel & daily vlogs[cite: 1] |
| **Soft Diaries** | Hoshi | Vlog (82 BPM) | GRWM & aesthetic clips[cite: 1] |
| **Wobble Walk** | Mellow Fox | Funny (112 BPM) | Memes & comedy sketches[cite: 1] |
| **Epic Reveal** | Nerida | Cinematic (90 BPM) | Drone shots & travel reveals[cite: 1] |

---

## 🏗 System Design & Architecture

Aurora is structured entirely around native client-side web primitives without relying on an external server or build pipeline[cite: 1]. The architecture divides cleanly into three functional layers:
