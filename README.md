# Technics RS-M250 Hybrid 📼
Technics RS-M250 Hybrid 📼
A high-fidelity, skeuomorphic web-based cassette deck simulator that bridges vintage analog aesthetics with modern digital audio playback. This project is a tribute to the legendary Technics RS-M250, utilizing the Web Audio API to provide an interactive Hi-Fi experience directly in your browser.

## 🔗 Live Demo
🚀 Launch the Live Demo [**Launch the Cassette Deck**](https://babuptx.github.io/technics-rs-m250/)

✨ Features

🎨 Visual & Aesthetic Accuracy
Skeuomorphic Design: Features a realistic brushed nickel faceplate, vintage wood cabinet enclosure, and tactile 3D mechanical keys.

Dynamic Cassette Mechanism: * Reels spin and stop based on the transport state (PLAY, REW, FF).

The tape supply visually grows and shrinks in real-time as the song progresses.

3D Jewel Case: A functional 3D case that flips on click. The front displays album art, while the back reveals a dynamically generated tracklist from your loaded files.

📊 Real-Time Visualizers
Analog VU Meters: Dual-channel needles with a warm amber backlight that reacts to audio transients.

VFD LED Monitors: Classic horizontal stereo output bars with high-contrast peak indicators.

25-Band Spectrum Analyzer: A Real-Time Analyzer (RTA) calibrated from 25Hz to 16kHz, featuring "Peak Hold" falling tiles for a vintage digital feel.

🎧 Audio Engineering & Controls
Tone Control: Fully functional Bass and Treble knobs (utilizing Biquad filters) to shape your sound.

Precision Transport: Play, Pause, Stop, Fast Forward (Next), Rewind (Prev), and Precision Seek (+/- 5 seconds).

Playback Modes: Support for Mix (Shuffle) and Loop (All/One).

Tape Bias Selectors: Switch between Normal, CrO2, and Metal modes to dynamically update the cassette's visual label design.

📂 Playlist Management
Local Folder Loading: Click the EJECT button to load a local directory of music.

Supported Formats: MP3, WAV, FLAC, OGG, and M4A.

Metadata Integration: Automatically extracts folder names for album titles and scans for image files to display as inlay art.

🛠️ Technical Stack
Interface: HTML5 & CSS3 (3D Transforms & Grid): For the complex skeuomorphic UI, 3D transforms, and containerization.
Web Audio API: EngineWeb Audio API (BiquadFilter, AnalyserNode)- Drives the real-time frequency analysis, filtering, and audio routing.
Audio: EngineWeb Audio API (BiquadFilter, AnalyserNode)
Logic: Vanilla JavaScript (ES6+): Handles the logic for the tape mechanism animations and local file system interactions.
Icons: Custom SVG


📖 Operating Instructions
Power On: Click the large circular POWER button to initialize the deck.

Load Music: Click the EJECT button to select a folder on your device containing audio files.

Flip the Case: Click the Jewel Case on the right to flip between the Album Art and the Tracklist.

Toggle Displays: The VFD LED bars and the Spectrum Analyzer can be toggled ON/OFF by clicking their respective display areas.

Adjust Tone: Click and drag vertically on the Bass, Treble, or Volume knobs to adjust levels.

🤝 Credits & Contacts:
Designed & Developed by an Audiophile like you (Chittaranjan Panda - Babu)


⚙️ Feedback & Support: Have questions or suggestions? I'd love to hear from you. 📧 babuptx@gmail.com