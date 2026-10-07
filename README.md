# Block Dash — PWA/Android packaging version

This folder is a mobile-friendly playable game plus:
- `manifest.json` for Progressive Web App installation
- `sw.js` for offline caching
- `icon.svg` for the app icon

## Phone-only publishing route
1. Upload these files to a public GitHub repository.
2. Enable GitHub Pages.
3. Open the resulting HTTPS URL on your phone and test the game.
4. Submit that URL to PWABuilder.
5. Use PWABuilder's Android package flow to generate the Google Play package.
6. Upload the generated Android App Bundle to Google Play Console.

Google Play still requires the developer-account setup and, for newer personal accounts, a closed test with at least 12 testers continuously for 14 days before production access.
