# Enhanced Piano

An interactive piano application built with HTML, CSS, and JavaScript that allows you to play music using your keyboard, mouse, or touch screen.

## Features

- Play piano notes using keyboard keys, mouse clicks, or touch screen
- Multiple piano sound options (Grand Piano, Electric Piano, Synth)
- Volume control
- Recording and playback functionality
- Responsive design that works on desktop and mobile devices
- Visual feedback for key presses
- Keyboard hints on hover

## How to Use

1. Open the application in a web browser
2. Use your keyboard keys (A-K for white keys, W,E,T,Y,U,O,P for black keys)
3. Click or touch the piano keys on screen
4. Use the controls at the top to:
   - Change the piano sound
   - Adjust the volume
   - Record your performance
   - Play back your recording
   - Stop playback

## Technical Details

The application uses:
- HTML5 Audio API for sound playback
- CSS3 for animations and styling
- Vanilla JavaScript for interactivity
- Responsive design principles for mobile compatibility

## Setup

1. Clone this repository
2. Add your sound files to the appropriate directories:
   - `sounds/grand/` for grand piano samples
   - `sounds/electric/` for electric piano samples
   - `sounds/synth/` for synth samples
3. Open `piano.html` in a web browser

## Sound Files

The application expects sound files in WAV format. Each note should be named according to its MIDI note number (e.g., "040.wav" for middle C).

## Browser Support

The application works best in modern browsers that support:
- HTML5 Audio
- CSS3 Transitions
- Touch Events
- ES6+ JavaScript features

## License

This project is open source and available under the MIT License. 