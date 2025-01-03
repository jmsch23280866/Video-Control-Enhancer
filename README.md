# Video Speed & Volume Adjuster with HUD

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[繁體中文](README_ZH.md)

A convenient browser userscript that allows you to easily adjust video playback speed and volume using mouse controls, with real-time visual feedback.

## Features

- Adjust video playback speed using Ctrl + Mouse Wheel
- Control volume using Right-Click + Mouse Wheel
- Real-time HUD display in the center of the video
- Support for all websites with HTML5 video players
- Clean interface that doesn't interfere with the original webpage

## Usage

### Playback Speed Adjustment
- Hold Ctrl key
- Scroll Up: Increase playback speed
- Scroll Down: Decrease playback speed
- Speed range: 0.1x ~ 16.0x

### Volume Control
- Hold Right Mouse Button
- Scroll Up: Increase volume
- Scroll Down: Decrease volume
- Volume range: 0% ~ 100%

## Installation

1. First, install a userscript manager:
   - Chrome: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - Firefox: [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)

2. Click the following link to install the script:
   - [Install Script](installation_link) <!-- Replace with actual installation link -->

## Technical Details

- Pure JavaScript implementation
- No external library dependencies
- Uses MutationObserver to monitor DOM changes
- Supports dynamically loaded video elements

## Compatibility

- Supports all major browsers (Chrome, Firefox, Edge, Safari)
- Works with any website using standard HTML5 `<video>` elements

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Contributing

Issues and Pull Requests are welcome to help improve this project!

## Author

Agent_E04 ([@jmsch23280866](https://github.com/jmsch23280866))

## AI Assistance Statement

This project was developed with assistance from Claude 3.5 Sonnet and ChatGPT AI, including code optimization suggestions and documentation writing. We believe in transparent disclosure of AI participation to promote open-source community development.

## Changelog

### 1.0.0 (2025-01-03)
- Initial release
- Implemented basic playback speed and volume control features
- Added HUD display functionality 
