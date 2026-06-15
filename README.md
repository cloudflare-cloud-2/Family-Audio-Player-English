# Family Audio Player — English (KJV)

English (King James Version) audio Bible web app — 1189 chapters, each pairing chapter audio with its text.

- Online / Offline Bible reading & listening
- Saves & bookmarks your progress automatically as you read
- 1189 audio chapters (KJV) paired with chapter text
- English companion to the Tagalog edition

## Hosting (CDN)

This repository is served as static files via a CDN such as jsDelivr:

    https://cdn.jsdelivr.net/gh/cloudflare-cloud-2/Family-Audio-Player-English@main/index.html

## Layout

- `index.html`, `app.js`, `styles.css` — the runtime web app
- `audio/p1` (0001–1000), `audio/p2` (1001–1189) — chapter audio
- `data/text/p1` (0001–1000), `data/text/p2` (1001–1189) — chapter text

The generator (`build_english.py`) and its source assets (`kjv.json`, `English-Audio/`) are intentionally not committed.
