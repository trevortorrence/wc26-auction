# WC26 Auction Draft

World Cup 2026 auction pick'em game for 13 players.

## Setup
1. Open the site URL
2. Enter a commissioner PIN to create the game
3. Share the URL with all 13 players — they select their name to join
4. Randomize draft order, then start the auction

## How it works
- **$100 budget** per player, **3 teams** each, **39 teams** total claimed from 48
- **Snake nomination order** across 3 rounds
- **Commissioner** runs the auction verbally (great for video calls), records each sale in the app
- All players see live updates via Firebase

## Tech
- React 18 (CDN), Babel standalone, Firebase Realtime Database
- Single `index.html` — no build step required
