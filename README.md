# Minimalist Media Player

A simple media player using HTML, JavaScript and [Tailwind CSS](https://tailwindcss.com) for styling. The interface embraces a calm, Notion‑like aesthetic with generous spacing and subtle interactions. Typography is provided by the [Inter](https://fonts.google.com/specimen/Inter) font for a modern feel, and controls include soft hover animations.

## Features
- Play/Pause control with dynamic icon
- Seek bar with smooth updates
- Current time display
- Volume slider

## Windows setup
1. Install [Node.js](https://nodejs.org/) for Windows.
2. Run `npm install` in this folder to install Electron.
3. Start the desktop app with `npm start`.

Place an audio file named `sample.mp3` in `src/media/` (or adjust the `audio` element's `src`) and the Electron window will load it.

## What this project lacks
- Packaging steps to create a standalone `.exe` installer
- Playlist management or file browsing
- Keyboard shortcuts and advanced playback controls
