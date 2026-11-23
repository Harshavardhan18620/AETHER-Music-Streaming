# AETHER // Zero-G Spatial Audio & Music Streaming

> **AETHER** is a futuristic, zero-gravity spatial music streaming web application featuring an in-browser Web Audio API synthesizer, real-time reactive audio visualizer, interactive physics-driven floating cards, synchronized lyrics, dynamic queue management, and a Mood Gravity Mixer.

![AETHER Preview](https://img.shields.io/badge/Audio-Spatial%20Web%20Audio%20API-8B5CF6?style=for-the-badge)
![UI](https://img.shields.io/badge/Design-Cyberpunk%20%2F%20Glassmorphism-06B6D4?style=for-the-badge)
[![Live Demo](https://img.shields.io/badge/Live%20Deployment-GitHub%20Pages-brightgreen?style=for-the-badge)](https://harshavardhan18620.github.io/AETHER-Music-Streaming/)

---

## 🌐 Live Application

- **Live Deployed Web App**: [https://harshavardhan18620.github.io/AETHER-Music-Streaming/](https://harshavardhan18620.github.io/AETHER-Music-Streaming/)
- **GitHub Repository**: [https://github.com/Harshavardhan18620/AETHER-Music-Streaming](https://github.com/Harshavardhan18620/AETHER-Music-Streaming)

---

## 🌟 Key Features

### 🎧 In-Browser Web Audio API Synthesizer
- **Harmonic Sound Engine**: Built-in polyphonic pad oscillators, kicks, hats, and arpeggios that generate real-time music for every track.
- **Dynamic DSP Chain**: Real-time adjustable low-shelf filter (sub-bass), resonant low-pass filter (energy/brightness), and tempo-synced feedback delay (spatial echo).
- **Zero External Audio Files Needed**: Synthesizer and embedded artwork ensure 100% offline and standalone capability.

### 🌌 Antigravity Zero-G Physics Mode
- **Floating Cards**: Toggle Antigravity mode to release cards from the DOM grid into a floating zero-gravity state.
- **Inertia Drag & Drop**: Grab and fling playlist or album cards with velocity-based momentum and rotation physics.
- **Snap to Orbit**: Instant "Reset Gravity" button snaps all elements back to their gravitational coordinates.
- **3D Magnetic Tilt**: Interactive perspective tilt on hover responding to cursor coordinates.

### 📊 Real-Time Audio Visualizer
- **44-Band Equalizer**: Live frequency analyser reading output audio data directly from the Web Audio analyser node.
- **Gradient Glow**: Responsive violet-cyan-magenta neon bars positioned behind the floating player dock.
- **Toggleable Display**: Can be hidden or shown directly from the dock controls.

### 🎛️ Mood Gravity Mixer
- **Real-Time Sound Sculpting**: Live sliders for Energy, Bass, BPM, and Spatial Echo.
- **Smart Gravity Recommender**: Dynamically calculates euclidean distance between your sonic profile and all 12 spatial tracks to recommend the best matches in real time.

### 🎵 Persistent Floating Player Dock
- **Spinning Vinyl Disc**: Vinyl grooves with track-specific vinyl center labels and smooth rotation synced to play/pause state.
- **Synced Lyrics Drawer**: Karaoke-style timestamped lyrics that highlight as the track progresses.
- **Interactive Drag-and-Drop Queue**: Reorder upcoming tracks seamlessly via native drag-and-drop.
- **Full Playback Controls**: Shuffle, repeat (off / all / one), scrub seek bar, volume & mute controls.

### 📱 Responsive Futuristic App Shell
- **Desktop Sidebar**: Quick navigation, custom playlist list, and live synth BPM telemetry monitor.
- **Mobile Drawer**: Smooth slide-over navigation for smaller touchscreens.
- **Global Search & Shortcuts**: `⌘K` / `Ctrl+K` quick search filtering artists, albums, tracks, and playlists.
- **Playlist Creator Modal**: Custom playlist generator with mood tagging and track picker.

---

## 🛠️ Technology Stack

- **Markup & Layout**: Semantic HTML5, CSS3, Flexbox, CSS Grid
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Dark Mode, Glassmorphism, Ambient Drift Keyframes)
- **Icons**: [Lucide Icons](https://lucide.dev/)
- **Typography**: [Inter](https://fonts.google.com/specimen/Inter) & [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk)
- **Audio Engine**: Native Browser [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) (OscillatorNode, BiquadFilterNode, DelayNode, GainNode, AnalyserNode)

---

## 🚀 Getting Started

No build step or dependencies required!

### Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Harshavardhan18620/AETHER-Music-Streaming.git
   ```
2. Navigate into the folder:
   ```bash
   cd AETHER-Music-Streaming
   ```
3. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari):
   ```bash
   start index.html
   ```

---

## 📄 License

This project is licensed under the MIT License - feel free to customize and build upon it!
