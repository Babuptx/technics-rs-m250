# Technics RS-M250 Hybrid 📼
Technics RS-M250 Hybrid 📼

A high-fidelity, skeuomorphic web-based cassette deck simulator that bridges vintage analog aesthetics with modern digital audio playback. This project is a tribute to the legendary Technics RS-M250, utilizing the Web Audio API to provide an interactive Hi-Fi experience directly in your browser.

## 🔗 Live Demo
🚀 Launch the Live Demo [**Launch the Cassette Deck**](https://babuptx.github.io/technics-rs-m250/)


🤝 Credits & Contacts:
Designed & Developed by an Audiophile like you (Chittaranjan Panda - Babu)


⚙️ Feedback & Support: Have questions or suggestions? I'd love to hear from you. 📧 babuptx@gmail.com





# Technics RS-M250 Hybrid 📼

A high-fidelity, skeuomorphic web-based cassette deck simulator that bridges vintage analog aesthetics with modern digital audio playback. This project is a tribute to the legendary Technics RS-M250, utilizing the Web Audio API to provide an interactive Hi-Fi experience directly in your browser.

## 🔗 Live Demo
🚀 Launch the Live Demo [**Launch the Cassette Deck**](https://babuptx.github.io/technics-rs-m250/)

## ✨ Features

### 🎨 Visual & Aesthetic Accuracy
- **Skeuomorphic Design**: Features a realistic brushed nickel faceplate, vintage wood cabinet enclosure, and tactile 3D mechanical keys
- **Dynamic Cassette Mechanism**: 
  - Reels spin and stop based on the transport state (PLAY, REW, FF)
  - Tape supply visually grows and shrinks in real-time as the song progresses
  - Realistic spin animations with different speeds for various modes
- **3D Jewel Case**: A functional 3D case that flips on click. The front displays album art, while the back reveals a dynamically generated tracklist from your loaded files
- **Authentic Lighting**: Warm amber backlighting on VU meters with realistic flickering effects

### 📊 Real-Time Visualizers
- **Analog VU Meters**: Dual-channel needles with dynamic backlighting that responds to audio transients
- **VFD LED Monitors**: Classic horizontal stereo output bars with high-contrast peak indicators (46-segment per channel)
- **25-Band Spectrum Analyzer**: Real-Time Analyzer (RTA) calibrated from 25Hz to 16kHz, featuring "Peak Hold" falling tiles for a vintage digital feel
- **Toggleable Displays**: Both LED meters and spectrum analyzer can be toggled on/off for performance optimization

### 🎮 Enhanced User Interaction
- **Keyboard Shortcuts**: Complete keyboard navigation support with hover tooltip display (5-second hover)
- **Smart Auto-Play**: Automatically starts playing the first song when loading a new music folder (when powered on)
- **Responsive Controls**: Touch and mouse support with proper state management
- **Accessibility Features**: Screen reader support, ARIA labels, and reduced motion preferences

### 🎧 Audio Engineering & Controls
- **Tone Control**: Fully functional Bass and Treble knobs (±10dB) using Biquad filters
- **Precision Transport**: Play, Pause, Stop, Fast Forward (Next), Rewind (Prev), and Precision Seek (+/- 5 seconds)
- **Playback Modes**: Support for Mix (Shuffle) and Loop (All/One) with visual feedback
- **Tape Bias Selectors**: Switch between Normal, CrO2, and Metal modes to dynamically update the cassette's visual label design

### 📂 Playlist Management
- **Local Folder Loading**: Click the EJECT button to load a local directory of music
- **Supported Formats**: MP3, WAV, FLAC, OGG, and M4A
- **Metadata Integration**: Automatically extracts folder names for album titles and scans for image files
- **Art Rotation**: Automatic rotation through multiple album art images when available
- **Enhanced File Handling**: Robust error handling for corrupted or unsupported files

### ⌨️ Keyboard Shortcuts
| Shortcut | Function | Notes |
|----------|----------|-------|
| **Space/K** | Play/Pause | Toggle playback |
| **S** | Stop | Stop and reset |
| **←** | Seek -5s | Quick seek backward |
| **Shift+←** | Previous Track | Skip to previous |
| **→** | Seek +5s | Quick seek forward |
| **Shift+→** | Next Track | Skip to next |
| **M** | Toggle Shuffle | Random playback order |
| **L** | Toggle Loop | Loop modes (All/One) |
| **E** | Eject/Load | Open folder selector |
| **P** | Power | On/Off |
| **Ctrl+R** | Reset Counter | Reset tape counter |
| **H/?** | Help | Show user manual |
| **Esc** | Close Dialogs | Exit modals |

*💡 Hover over the deck for 5 seconds to see all keyboard shortcuts*

## 🛠️ Technical Stack
- **Interface**: HTML5 & CSS3 (3D Transforms, Grid, Custom Properties) - Complex skeuomorphic UI with containerization
- **Web Audio API**: Audio processing engine (BiquadFilter, AnalyserNode, GainNode) - Real-time frequency analysis, filtering, and audio routing
- **JavaScript ES6+**: Application logic with proper error handling and JSDoc documentation
- **SVG Icons**: Custom scalable vector graphics for UI elements
- **File API**: Local file system interaction with proper memory management
- **CSS Animations**: Hardware-accelerated animations with reduced motion support

## 📖 Operating Instructions

### Basic Operation
1. **Power On**: Click the large circular POWER button to initialize the deck
2. **Load Music**: Click the EJECT button to select a folder containing your audio files
3. **Auto-Play**: The first song will automatically start playing when loaded (if powered on)
4. **Flip the Case**: Click the Jewel Case on the right to flip between Album Art and Tracklist

### Advanced Controls
- **Toggle Displays**: Click the VFD LED bars or Spectrum Analyzer to toggle them ON/OFF
- **Adjust Tone**: Click and drag vertically on the Bass, Treble, or Volume knobs
- **Keyboard Navigation**: Use keyboard shortcuts for quick access to all functions
- **Hover Tooltips**: Hover over the deck for 5 seconds to display all keyboard shortcuts

### Performance Tips
- Toggle off spectrum analyzer and LED displays on older devices
- Use smaller window sizes for better performance
- Close other browser tabs when using the deck

## 🔧 Recent Enhancements (v5.18)
- **Enhanced Code Quality**: Comprehensive JSDoc documentation and improved error handling
- **Keyboard Shortcuts**: Full keyboard navigation with tooltip display system
- **Auto-Play Feature**: Automatic playback of first song when loading folders
- **Memory Management**: Proper cleanup of object URLs and audio contexts
- **Accessibility**: Improved screen reader support and reduced motion preferences
- **Robust Error Handling**: Graceful fallbacks for unsupported features
- **Touch Support**: Enhanced touch interactions for mobile devices

## 🤝 Credits & Contacts
Designed & Developed by an Audiophile like you (Chittaranjan Panda - Babu)

⚙️ **Feedback & Support**: Have questions or suggestions? I'd love to hear from you. 📧 babuptx@gmail.com

---

### 📂 Repository
- **GitHub Repository**: [View Source Code](https://github.com/babuptx/technics-rs-m250)
- **README**: This documentation file
- **Live Demo**: [Launch the Cassette Deck](https://babuptx.github.io/technics-rs-m250/)

---

*This application operates entirely in your browser - no files are uploaded to external servers. Enjoy your music responsibly and support artists by using legally obtained content.* 🎵
