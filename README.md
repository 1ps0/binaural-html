# Therapeutic Frequencies Dashboard

A browser-based application for playing binaural beats, solfeggio frequencies, and other therapeutic tones. This dashboard allows you to explore and use sound frequencies that may help with relaxation, focus, meditation, and other cognitive states.

![Dashboard Screenshot](screenshot-placeholder.jpg)

## Features

- Play binaural beats for different brain wave states (delta, theta, alpha, beta, gamma)
- Experience solfeggio frequencies with specific healing properties
- Explore special frequencies like Schumann Resonance
- Mix multiple frequencies together
- Control volume and manage active tones
- Pin your favorite frequencies for quick access
- Toggle between card and list views
- Mobile-friendly interface

## How It Works

The application uses the Web Audio API to generate precise sine wave tones:

- **Binaural Beats**: Plays slightly different frequencies in each ear, creating a perceived beat at the difference frequency. Requires headphones for proper effect.
- **Pure Tones**: Plays single frequencies associated with different healing properties.

## How to Use

1. Open the HTML file in any modern web browser
2. Click the "Play" button on any frequency card to start playing that tone
3. Use the volume slider to adjust the sound level
4. Toggle between card and list views for different browsing experiences
5. Pin your favorite frequencies for quick access
6. View information about frequency therapy in the "Information" tab

## Planned Improvements

The following improvements are planned for future versions:

### High Priority
- **Pinned Items Improvement**: Change pinned items to move the original items rather than creating clones
- **Remove Test Button**: Remove unused utility button from the interface
- **Add "Unpin All" Feature**: Add functionality to unpin all items at once via a control bar button

### Medium Priority
- **List View Consistency**: Standardize play/pause button positioning in list view
- **Text Handling**: Add expand functionality for descriptions in list view with critical info at the start
- **Control Bar Optimization**: Move card/list toggle to the permanent control bar
- **Mobile Layout**: Improve permanent bar layout and functionality on mobile devices

### Low Priority
- **Pin Alignment**: Fix pin positioning in list view to be consistently located relative to item names

## Using on Desktop

Simply open the HTML file in any modern web browser (Chrome, Firefox, Safari, Edge).

## Using on Mobile Devices

### iOS (iPhone, iPad)
iOS doesn't allow direct opening of HTML files with audio functionality. Use one of these methods:

1. **Using a File Manager App**:
   - Install a file manager app like Documents by Readdle
   - Transfer the HTML file to your device via AirDrop, email, or cloud storage
   - Open the file using the app's built-in browser

2. **Using a Web Server**:
   - Install an app like "Web Server for Chrome" on your computer
   - Serve the HTML file on your local network
   - Visit the local URL on your iOS device

3. **Using GitHub Pages (if public sharing is acceptable)**:
   - Upload to a GitHub repository
   - Enable GitHub Pages
   - Access via the provided URL

### Android
Android allows more direct file access:

1. **Direct File Opening**:
   - Transfer the HTML file to your device
   - Use the Files app to locate the file
   - Tap to open in your preferred browser

2. **Using a Web Server App**:
   - Install an app like "Simple HTTP Server"
   - Serve the file directly from your device
   - Access via localhost in your browser

### Offline Usage
For completely offline use on mobile:

1. Download all files to your device
2. Use a file manager with a built-in browser (like Documents by Readdle on iOS)
3. The app will work without any network requests once loaded

## Browser Compatibility

- Chrome 58+
- Firefox 53+
- Safari 11+
- Edge 16+
- Mobile browsers with Web Audio API support

## Notes on Frequency Therapy

This application is provided for experimental and recreational purposes. The therapeutic effects of specific frequencies are still being researched scientifically. Always use at a comfortable volume level and consult healthcare professionals for medical concerns.

## Credits

- Web Audio API for audio generation
- Inspired by research on frequency therapy and binaural beats

## Version History

See [CHANGELOG.md](CHANGELOG.md) for version details and updates. 