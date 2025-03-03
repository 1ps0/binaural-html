# Binaural Beats & Healing Frequencies

A web-based application for exploring and experiencing therapeutic frequencies through binaural beats, solfeggio tones, and sound therapy. Built with vanilla JavaScript and modern web technologies.

## Features

- **Multiple Frequency Types**
  - Binaural Beats for brainwave entrainment
  - Solfeggio Frequencies for traditional healing
  - Special frequencies including Earth resonance (Schumann)

- **Intuitive Interface**
  - Dark/Light theme support
  - Card and List view options
  - Responsive design for all devices
  - Touch-friendly controls

- **Advanced Audio Features**
  - Real-time frequency generation
  - Volume control with smooth transitions
  - Multiple simultaneous tones
  - Binaural beat stereo separation

- **Organization**
  - Search functionality
  - Category filtering
  - Pin favorite frequencies
  - Active tones display

## Categories

- **Focus** (Beta/Gamma waves): 14-40 Hz
- **Meditation** (Theta waves): 4-8 Hz
- **Sleep** (Delta waves): 0.5-4 Hz
- **Relaxation** (Alpha waves): 8-14 Hz
- **Healing** (Solfeggio): Various frequencies

## Usage

1. Visit the hosted version at: https://1ps0.github.io/binaural/
2. Use quality headphones for optimal binaural beat effects
3. Start with lower volumes and shorter sessions
4. Pin your favorite frequencies for quick access
5. Use the search to find specific frequencies

## Running Locally

### Desktop
Simply drag `index.html` into your browser window. For Chrome/Edge users, this is all you need.

Note: Some browsers may require a local server for audio to work. If needed:
```bash
# Using Python
python -m http.server 8000
# Then visit http://localhost:8000
```

### iOS (iPhone/iPad)
1. Long press the download link for `index.html` and choose "Download Linked File"
2. Tap "Downloads" in Safari
3. Tap the downloaded file
4. Choose "Save to Files"
5. Select a location (like "On My iPhone" or "iCloud Drive")
6. Open the Files app, navigate to where you saved it
7. Tap the file to open in Safari

### Android
1. Download `index.html` to your device
2. Open with Chrome directly from your Downloads folder
3. Optional: Add to Home Screen for quick access

## Technical Details

- Single file architecture (index.html)
- No external dependencies
- Uses Web Audio API for precise frequency generation
- Local storage for user preferences
- Mobile-first responsive design

## Browser Support

- Chrome/Edge (Recommended)
- Firefox
- Safari
- Mobile browsers with Web Audio API support

## Development

1. Clone the repository
2. Serve index.html through a web server (required for audio context)
3. Make changes and test thoroughly
4. Submit pull requests with clear descriptions

## Version History

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

Current Version: 4.1.0 (Build 20250303.1)

## License

MIT License - See LICENSE file for details 