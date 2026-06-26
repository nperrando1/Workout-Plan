# Strength Training Plan

Interactive 16-week strength training program with adaptive progression, built as a single-page HTML app.

**Live dashboard:** [https://phillrich13.github.io/Workout-Plan/](https://phillrich13.github.io/Workout-Plan/)

## Features

- **16-week progressive program** across 4 phases (Foundation, Building, Strength, Performance)
- **3 training days/week** — Lower Body + Core, Upper Body Push/Pull, Hybrid day
- **Adaptive difficulty** — rate each workout 1-5, get adjustment recommendations for the following week
- **Firebase real-time sync** — workout data syncs automatically across all devices
- **Offline capable** — falls back to browser localStorage when offline
- **Planet Fitness compatible** — machines, dumbbells, Smith machine, cables only
- **Exercise guide** with form instructions, warm-up, and cool-down routines

## Usage

Open `index.html` in any browser, or visit the live GitHub Pages link above. Data syncs automatically via Firebase — no setup needed.

## Data

All workout data is stored in Firebase Realtime Database and syncs in real-time across devices. A local copy is kept in the browser's localStorage as a fallback.

Use the **Export JSON** button to download a backup, or **Import JSON** to restore from a backup file.
