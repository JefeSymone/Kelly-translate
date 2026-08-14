# Kelly Translate Web

This is the Safari/Home Screen version.

## Features
- English → Spanish and Spanish → English
- Voice input when supported by Safari/iPhone
- Spoken translation playback
- Swap languages
- Copy translations
- Saved phrases
- Recent translation history
- Home Screen / PWA support
- Offline app-shell caching

## Important limitation
New translations use the MyMemory web translation API, so new translations require internet.
The app itself can reopen offline, and saved phrases/history remain available locally.
Safari speech recognition may also use a network service.

## How to publish it
Upload the contents of this folder to any static HTTPS host such as GitHub Pages,
Cloudflare Pages, Netlify, or Vercel. Then open the HTTPS address on iPhone Safari,
tap Share → Add to Home Screen.

No API key is required for the basic MyMemory endpoint used in this version.
The MyMemory endpoint has usage limits and a 500-byte query limit.
