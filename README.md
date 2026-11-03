# LAST CITY: APOCALYPSE
3D browser co-op zombie survival prototype using Three.js and WebSockets.

## Deploy on Render
1. Upload all files to a GitHub repository, preserving `public/index.html`.
2. Render → New → Web Service → connect repository.
3. Language: **Node** (NOT Docker). Build command: `npm install`. Start command: `npm start`.
4. Deploy. Render provides a public HTTPS URL. Everyone opens the SAME URL to play together.

## Local test
`npm install` then `npm start`, visit `http://localhost:3000`.

## Controls
WASD move, mouse look, left click shoot, Shift sprint, R reload, E loot/repair, F truck, Enter chat.

## Important limitations
This is a browser-based multiplayer prototype, NOT GTA-grade graphics. Simple procedural geometry and low-poly zombie characters; no high-resolution licensed assets, complex animations, or production-grade security. State is held in memory and resets when Render restarts. Multiplayer server is needed; GitHub Pages alone cannot host WebSockets. Three.js loads from a CDN, requiring internet access. Free Render instances may sleep or have usage restrictions.
