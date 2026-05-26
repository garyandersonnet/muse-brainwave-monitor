# Muse Brain Waves

A beautiful, self-contained web app for real-time brain wave monitoring using the Muse 2 / Muse S EEG headband via Web Bluetooth.

## Features

- Live 4-channel (or 5 with AUX) EEG waveforms
- Real-time spectrogram
- Band power visualization (Delta, Theta, Alpha, Beta, Gamma)
- Mental state detection with meditation score
- Gyroscope-based head position tracking with visual indicator
- Blink detection with animated eyes on the head icon
- AUX probe support
- CSV recording of raw data
- Audio sonification feedback
- Fully functional in Demo mode (no hardware required)

## How to Use

1. Open `muse-brainwave-monitor.html` in Chrome or Edge.
2. For demo: Click "Demo"
3. For real Muse: Check "Enable AUX Probe" if desired, then click "Connect Real Muse"

## Requirements for Real Hardware

- Muse 2 or Muse S
- Chrome or Edge browser (desktop or Android)
- Bluetooth enabled
- On macOS: Grant Bluetooth permission to the browser in System Settings

## License

MIT

Built as a single-file, zero-dependency experience.