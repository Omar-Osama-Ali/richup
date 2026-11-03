# Richup-inspired browser game

Independent frontend recreation of a property-trading board-game experience. The project is designed for GitHub Pages and supports private friend rooms using PeerJS/WebRTC.

## Run locally
Open `index.html` in a modern browser, or run `python -m http.server 8000` and visit `http://localhost:8000`.

## Publish to GitHub Pages
Upload the contents of this folder to the root of the `richup` repository, commit, and wait for GitHub Pages to deploy. Hard-refresh the published page after deployment.

## Private multiplayer
1. Enter a nickname and select **Create a private game**.
2. Share the room code or invite URL.
3. Friends open the same published website, enter the code and join.
4. The host starts when at least two players are connected. Up to six players are supported.

The host's browser tab must remain open. PeerJS Cloud is used for signaling and WebRTC carries peer-to-peer game data. Some networks may require TURN relay support. This is a prototype; a dedicated authoritative backend is required for production-grade reliability and anti-cheat.

## Privacy and data
- No account registration, advertising pixels, analytics SDKs or payment processing are included.
- The nickname and cookie-notice preference are stored in browser `localStorage`.
- Room/game state is hosted temporarily in the host's browser and exchanged with connected players.
- PeerJS is a third-party dependency and its signaling service may process technical connection metadata.
- Privacy, terms and cookie notices are included in the interface. The operator's legal business name, address, contact details and governing jurisdiction were not supplied and must be completed before commercial/public production use.
- No child profile or date-of-birth field is collected. Do not ask children to submit personal information.

## Accessibility and interface
Includes skip link, keyboard focus states, semantic dialogs, reduced-motion support, responsive navigation, mobile layout, accessible status messaging, metadata, favicon and custom 404 page.

## Known limitations
The game is a functional prototype, not a complete rules-identical Richup implementation. Full auctions, even house/hotel building, mortgages, advanced trading, robust reconnect/recovery, server-side validation and anti-cheat are not implemented. No fake reviews, counters, business claims or tracking metrics are displayed.

This independent project is not affiliated with or endorsed by Richup. Third-party names and marks belong to their respective owners.
