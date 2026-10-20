# Whiteboard™ — download site

Landing + download page for **Whiteboard**, the offline drawing app for Windows (₦1,000 one-time per PC).

- Live site: https://whiteboard-e8n.pages.dev (Cloudflare Pages, direct upload: `npx wrangler pages deploy . --project-name=whiteboard`)
- App source + seller tools live in a separate local folder (not public here).

## Files

| File | Purpose |
|---|---|
| `index.html` | Landing page (favicons/OG point at the icon files) |
| `whiteboard-icon.ico` | Favicon + app icon |
| `whiteboard-thumb.png` | Hero + link-preview image |
| `Whiteboard-Portable-1.1.3.zip` | Portable ZIP (the only download offered) |

## Releasing a new version

1. Copy the new `Whiteboard-Portable-*.zip` into this folder.
2. Update the link + version string in `index.html`.
3. Commit + push `main`, then run `npx wrangler pages deploy . --project-name=whiteboard` (GitHub push alone does NOT deploy — deploy is direct upload).

© 2026 ststudiosng. Whiteboard™ is a trademark of ststudiosng.
