# Almost Perfect Pitch 🍑🎵

**Almost Perfect Pitch** is a browser-based ear-training tool for practicing **relative pitch** through **scale, mode, and jens recognition**.  
The app plays randomized pitch patterns using high-quality piano sounds and challenges you to identify their structure by ear.

No installation, no backend — everything runs entirely in the browser.

🌐 **Live demo:**  
https://mawssen.github.io/Almost_Perfect_Pitch/

---

## Features

- 🎹 **Real piano sound** using SoundFont playback (no MIDI setup required)
- 🎼 **Scale recognition mode**
  - Major, minor, modal, pentatonic, and harmonic scales
- 🎵 **Jens (tetrachord) recognition mode**
  - Ajam, Hejaz, Nahavand, Kord
- 🎯 **Configurable training settings**
  - Select pitch range (C2–C6)
  - Fixed or random direction (ascending / descending)
  - Choose which scales to include
  - Number of tests per session
- 👂 **Training-friendly UI**
  - Replay patterns
  - Reveal start note and direction on demand
  - Immediate feedback and scoring
- 📱 **Works on desktop and mobile**
  - Runs entirely in modern browsers
  - HTTPS-safe audio playback

---

## How It Works

1. Choose a test mode (**Scale** or **Jens**)
2. Press **Start Test**
3. Listen to the played pattern
4. Identify the correct scale or jens
5. Get instant feedback and move to the next test

The app focuses on **relative pitch**, not absolute/perfect pitch.

---

## Tech Stack

- **HTML / CSS / JavaScript**
- **Web Audio API**
- **soundfont-player** for piano playback
- Hosted via **GitHub Pages**

---

## Development

To run locally:
1. Clone the repository
2. Open `index.html` in a local web server (recommended) or via GitHub Pages  
   > Note: some browsers restrict audio when opened directly via `file://`

---

## Motivation

This project was built as a lightweight, practical tool for musicians who want to strengthen their listening skills—especially for **modal and non-Western scale systems**—without installing heavy software or using subscription-based apps.

---

## License

MIT License
