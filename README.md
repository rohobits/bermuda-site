# bermuda

Single-page site for Bermuda, a Denver tech house trio. Deployed from this repo to https://bermuda-site.vercel.app.

- `index.html` — the whole site (no build step).
- `bermuda-brand-guidelines.html` — brand identity reference (palette, type, voice).
- `images/` — site photos, resized for web.

## Updating the latest set

The "Press Play. Disappear." section embeds the SoundCloud player for the Bermuda profile, which plays the newest upload first. Upload the new set to SoundCloud and it shows up automatically. To pin a specific track instead, replace the URL-encoded profile URL in the iframe `src` in `index.html` with the track URL.

Audio files should not be committed to this repo; host them on SoundCloud.
