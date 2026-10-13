# Whiteboard™ — download site

Landing + download page for **Whiteboard**, the offline drawing app for Windows (₦1,000 one-time per PC).

- Live site: https://whiteboard.pages.dev (Cloudflare Pages, deploys from `main`)
- App source + seller tools live in a separate local folder (not public here).

## Files

| File | Purpose |
|---|---|
| `index.html` | Landing page (favicons/OG point at the icon files) |
| `whiteboard-icon.ico` | Favicon + app icon |
| `whiteboard-thumb.png` | Hero + link-preview image |
| `Whiteboard-Setup-1.1.1.exe` | Windows installer |
| `Whiteboard-Portable-1.1.1.zip` | Portable ZIP |

## Releasing a new version

1. Copy the new `Whiteboard-Setup-*.exe` / `Whiteboard-Portable-*.zip` into this folder.
2. Update the two links + version strings + SHA256 hashes in `index.html`.
3. Commit + push to `main` — Cloudflare redeploys automatically.

© 2026 ststudiosng. Whiteboard™ is a trademark of ststudiosng.
