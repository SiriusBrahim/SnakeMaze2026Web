# Snake Maze 2026 Web

An ad-free, installable PWA version of the retro Nokia-style Snake Maze game. This repository contains only the browser build; the Android/Tablet app is maintained separately in [SnakeMaze2026Android](https://github.com/6yildiz9-maker/SnakeMaze2026Android).

## Features

- Maze, Classic, Time Attack, and Survival game modes
- Custom maze editor, career statistics, achievements, and daily quests
- Touch, swipe, and keyboard controls
- Custom themes, sound, and offline play after the first visit
- Local browser storage; no account, ads, or analytics

## Development

```bash
npm ci
npm run dev
npm test
npm run lint
npm run build
```

The production build is written to `dist/`. The included GitHub Actions workflow runs tests, lint, and build for pushes and pull requests targeting `main`.
