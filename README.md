# Richup-inspired Frontend Demo

A responsive, browser-only property trading board game interface inspired by the public Richup landing page and gameplay concept.

## Run locally
Open `index.html` in a modern browser. For a local server, run:
`python -m http.server 8000`
Then visit `http://localhost:8000`.

## GitHub Pages
Upload the contents of this folder to the root of a GitHub repository, enable GitHub Pages from the `main` branch / root folder, and publish.

## Included
- Landing page, nickname entry, room browser, private-room lobby
- Responsive board UI with 40 spaces
- Local turn flow, dice, movement, property purchases, rent, taxes, cards, and bot turns
- LocalStorage nickname persistence
- Simulated room codes, bots, chat/trade entry points

## Limitations
Frontend-only demo. Rooms and invites are simulated, and no real network multiplayer, server persistence, account system, or synchronized chat is implemented. The gameplay is a lightweight demonstration rather than a complete rules-certified Monopoly engine.

This is an independent fan-style implementation using original code and styling. It is not affiliated with or endorsed by Richup.
