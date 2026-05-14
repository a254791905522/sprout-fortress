# Sprout Fortress Publishing Package

This folder contains App Store publishing materials for **Sprout Fortress**.

## App Configuration

| Field | Value |
|---|---|
| App name | Sprout Fortress |
| Subtitle | Fantasy Tower Defense |
| Bundle ID | `com.rosewood.game.sproutfortress` |
| Version | 1.0.0 |
| Build | 1 |
| Team ID | 7ZR52UNP43 |
| Device support | iPhone only |
| Minimum iOS | 13.0 |
| Encryption | Uses non-exempt encryption: No |

## Files

- `index.html` - self-contained marketing/support page with embedded screenshots.
- `privacy.html` - privacy policy for an offline single-player game.
- `keywords.txt` - App Store keyword list, comma-separated with no spaces.
- `PUBLISH_CHECKLIST.md` - App Store Connect fields and submission checklist.
- `screenshots_65/` - iPhone 6.5-inch screenshots, 1284×2778.
- `screenshots_55/` - iPhone 5.5-inch screenshots, 1242×2208.

## Screenshot Order

1. `01_menu.png` - Main menu / first impression.
2. `02_level_select.png` - Level progress.
3. `03_gameplay.png` - Core defender placement gameplay.
4. `04_victory.png` - Win/progress moment.

## Manual Values Required Before Submission

Replace placeholders with your deployed URLs in App Store Connect:

- Privacy Policy URL: `https://YOUR_DOMAIN/privacy.html`
- Support URL: `https://YOUR_DOMAIN/index.html#support`
- Marketing URL: `https://YOUR_DOMAIN/index.html`

Do not submit placeholder URLs. Deploy `index.html` and `privacy.html` first, then verify both pages are publicly reachable without login.
