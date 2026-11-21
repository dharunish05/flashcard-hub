# Flashcard Hub

Responsive flashcard app with deck management, smooth 3D flip cards, learning ratings and Anki-inspired spaced repetition.

## Run locally
1. Install Node.js 18+.
2. Clone this repository.
3. Run `npm install`.
4. Run `npm run dev` and open the Vite local URL.

## Features
- Dashboard with streak, mastered count and per-deck progress.
- Create, search, split, merge and delete decks.
- Add and delete question/answer cards.
- Smooth flipping transition and 1–5 recall ratings.
- Lower ratings schedule cards sooner; higher ratings extend review intervals.
- Local browser storage and JSON export/import backups.

## Google Drive
The app currently provides a folder shortcut and JSON export/import, not automatic Drive synchronisation. To enable Drive API sync, configure a Google Cloud project, enable Google Drive API, create an OAuth 2.0 Web Client ID for the deployed origin, and implement the OAuth token flow. The supplied folder ID is `1vByS-lT-RPtRbh2ZVxOtzrUH-W4s_F_BV`. Anyone-with-link editor permission does not replace OAuth authentication for Drive API access.

## Data
Flashcards are stored in this browser's local storage. Export backups before clearing browser data or switching devices.
