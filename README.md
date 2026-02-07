# Simple Step Counter

A minimal web app that counts steps and walking time using your phone’s motion sensors.  
Designed to be clean, lightweight, and distraction-free.

## Features
- Live step counting (device motion)
- Walk timer (minutes & seconds)
- Start / Stop / Reset
- Local-only (no accounts, no analytics, no tracking)
- Modern neutral UI

## How it works
- Uses the browser `DeviceMotionEvent` to estimate steps
- Timer runs only while the app is active
- All data stays in the browser (no backend)

## Usage
1. Open the app on your phone (required for step counting)
2. Tap **Start**
3. Walk
4. Tap **Stop** to pause or **Reset** to clear

## Notes
- Step counting does not work on desktop/laptop
- Accuracy is approximate (not medical-grade)
- Data resets on refresh unless extended with localStorage

## Tech
- HTML
- CSS
- Vanilla JavaScript

## Hosting
Works on any static host (Vercel, Netlify, GitHub Pages).

## License
MIT
