# Technics RS-M250 Hybrid 📼

A high-fidelity, skeuomorphic web-based cassette deck simulator that bridges vintage analog aesthetics with modern digital audio playback.

## 🔗 Live Demo
[**Launch the Cassette Deck**](https://technics-deck-babuptx.netlify.app)
*(Note: If your Netlify URL is different, please edit this link)*

## 🌟 Features

### 🎨 Visual & Aesthetic
* **Realistic Design:** Brushed nickel faceplate with a vintage wood cabinet enclosure and 3D mechanical keys.
* **Cassette Physics:** "Racetrack" window featuring spinning reels with dynamic supply/take-up animation (tape cakes grow and shrink as the song plays).
* **Dynamic Lighting:**
    * **VU Meters:** Warm amber backlighting with high-contrast White/Red arcs.
    * **VFD Display:** 46-segment LED peak meters in Cyan/Red.
    * **Neon Indicators:** Functional LEDs for Power, Tape Type, and Playback modes.
* **3D Jewel Case:** An interactive album art display that flips to reveal the tracklist.

### 🎛 Audio & Functionality
* **Web Audio API Engine:** Built entirely on vanilla JavaScript.
* **Live EQ Controls:** Functional **Bass** and **Treble** knobs that alter audio frequencies in real-time.
* **Playback Logic:**
    * **Shuffle:** Randomizes tracks without repetition.
    * **Loop:** Toggles between "Loop One" and "Loop All".
* **Tape Simulation:** Selectable tape bias modes (Norm, CrO2, Metal) that change the cassette aesthetics.

## 🚀 How to Use
1.  Click the **EJECT** button to open the system file picker.
2.  Select a **Folder** on your computer containing audio files (MP3, WAV, FLAC).
3.  The deck will auto-load the playlist and album art.
4.  Press **PLAY** to start the tape.
5.  Use **Knobs** to adjust Volume and EQ.
6.  Click the **Jewel Case** to flip it and see the tracklist.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Advanced Gradients & Animations).
* **Logic:** Vanilla JavaScript.
* **Audio:** Web Audio API (`AnalyserNode`, `BiquadFilterNode`, `GainNode`).

---

### 👨‍💻 Credits
**Dedicated to all Audiophiles.**
Designed & Developed by **Chittaranjan Panda**.  Contact (babuptx [at] gmail)