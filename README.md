# Cleansweeper

> Turn your real-life cleaning routine into a game.

Cleansweeper is a Progressive Web App (PWA) that gamifies home cleaning. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build tools, no fuss. Install it on your iPhone home screen in seconds.

### Features

- **Room cycle tracking** — each room has its own cleaning schedule (kitchen every 2 days, bathroom every 3, bedroom every 7, etc.)
- **XP & leveling system** — earn points for cleaning, lose points for neglecting rooms too long
- **Daily quests** — timed cleaning challenges with XP rewards
- **Streak counter** — tracks how many days in a row you've cleaned something
- **Home levels** — your home progresses from "Messy Nest" through to "Gold Standard"
- **Offline-ready** — service worker caches the app for use without internet

### Tech stack

- Vanilla HTML/CSS/JavaScript
- PWA (manifest + service worker)
- localStorage for data persistence
- No dependencies, no build step

### Getting started

1. Clone or download this repo
2. Deploy the three files (`index.html`, `manifest.json`, `sw.js`) to any static host
3. Open in Safari on iPhone → Share → Add to Home Screen
4. Start cleaning (and leveling up)

### Deployment

This project is deployed via [Netlify](https://netlify.com). Any push to `main` triggers an automatic redeploy.
