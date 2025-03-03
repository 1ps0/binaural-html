# Changelog

## [4.2.0] - In Progress
### Added
- Frequency management modal with create, edit, and import/export functionality
- Custom frequency creation form
- Frequency editing capabilities
- Import/Export system for frequency collections
- Active tones section moved to main content area
- Improved mobile layout and responsiveness

### Changed
- Moved active tones display from control bar to main content
- Simplified control bar to single row layout
- Updated UI components for better mobile experience
- Improved theme system with better color management

### Fixed
- Stop All functionality improved
- Active tones display updates
- Pin/unpin system reliability
- Mobile layout issues

## [4.1.0] - 2024-03-03
### Added
- Version information display in info modal
- Build number tracking
- Improved audio initialization
- Dark/light theme toggle
- Responsive control bar
- Active tones display
- Category badges
- Search functionality
- Pin/unpin system
- View options (cards/list)

### Changed
- Simplified architecture to single file
- Improved audio context initialization
- Enhanced UI components
- Better error handling
- Mobile optimization
- Improved button states

### Fixed
- Audio initialization issues
- Mobile permission UI layout
- Volume control responsiveness
- Theme persistence
- Button hover states

### Initial Release
- Core binaural beats functionality
- Basic frequency presets
- Volume control
- Play/stop controls
- Info modal
- Responsive design foundation

## [v3.0.0] - 2023-06-15

### Added
- Card/list view toggle for different ways to browse frequencies
- Position toggle to switch control bar between top and bottom
- Multiple pinned cards functionality
- Minimize/maximize button for the persistent control bar
- Unified play/pause button with proper icons
- Mobile-optimized responsive design
- Touch-friendly controls for mobile devices
- Enhanced visual feedback for active frequencies

### Fixed
- Bug where cognitive enhancement card doesn't stop right ear oscillator
- Issue where "Stop All" doesn't properly stop right ear oscillators
- Fixed audio context handling for better performance
- Improved oscillator cleanup to prevent memory leaks
- Better error handling for audio playback issues

### Changed
- Control bar is now always visible instead of showing/hiding on scroll
- Pinned cards have unique styling to make them visually distinct
- Simplified UI with single play/pause button per card
- Improved mobile layout with optimized touch targets
- Enhanced responsive design for various screen sizes

### Known Issues
#### Core Functionality
- Pinned items create clones rather than moving the original items
- Test button lacks utility for regular users and should be removed
- No "unpin all" functionality in the control bar
- List view has inconsistent play/pause button positioning based on text length
- Card/list toggle located in main content rather than the persistent control bar
- Mobile permanent bar needs layout optimization
- Pin alignment in list view is inconsistent with item names

#### UI/Styling Issues
- Stop button doesn't update the play/pause button UI of the stopped element
- Volume slider control overspills its UI boundaries
- Active tones in permanent bar have poor contrast (black on blue text) - needs white text
- Filter bar lacks proper styling and consistency with the rest of UI
- In list view, the title, Hz indicator, and pin button text visually collide
- Pin button placement should be reconsidered in list view (possibly next to play/pause button)

## [v2.0.0] - 2023-05-03

### Added
- Support for mixing multiple frequencies simultaneously
- Active tones display showing currently playing frequencies
- Pin functionality to mark favorite frequencies
- Status indicator showing current playback state
- Tabbed interface with Information section
- Test button to sample different frequencies
- Filter functionality to search through frequencies

### Fixed
- Audio playback issues on certain browsers
- Volume control inconsistencies

### Changed
- Redesigned user interface with cards for each frequency
- Improved visual hierarchy and information display
- Enhanced binaural beat generation for more accurate frequencies

## [v1.0.0] - 2023-04-15

### Added
- Initial release with basic frequency playback
- Binaural beats for different brain states
- Solfeggio frequencies
- Special healing frequencies
- Volume control
- Basic documentation 