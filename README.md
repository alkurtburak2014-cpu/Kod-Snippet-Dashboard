# Kod Snippet Dashboard

A local, single-file code snippet dashboard with login, favorites, tags, collections, version history, and JSON import/export.

## Features
- Local user register/login (stored in browser localStorage)
- Add/edit snippets with language, tags, collection, and color
- Favorites filter
- Trash bin with restore
- Recommended snippets with infinite scroll
- Version history when you edit code
- JSON export/import for backup
- Dark/light theme toggle
- Info modal with shortcuts

## Run
Open `index.html` in any modern browser.

## Shortcuts
- Ctrl + K: Focus search
- Ctrl + Enter: Add snippet
- Ctrl + Shift + F: Toggle favorites filter
- ?: Open info modal
- Esc: Close open modal

## Data Storage
All data is saved locally in the browser localStorage. No server is required.

## Publish (GitHub Pages)
1. Push this repo to GitHub.
2. Go to Settings -> Pages.
3. Select the `main` branch and `/root` folder.
4. Save. GitHub will provide the public URL.
