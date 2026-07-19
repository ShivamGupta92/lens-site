# Lens — Public Pages

This repository hosts the public-facing pages for **Lens**, a Chrome extension that adds an AI chat side panel to any web page. Open it on a page and ask an AI questions about what you're reading — with your choice of provider (Google Gemini, OpenAI, or Anthropic) and your own API key. There's no Lens server, no account, and no telemetry: your data goes from your browser directly to the provider you chose.

This repo contains **only** the public pages below. The Lens extension source code lives in a separate, private repository.

## Pages

- **[About Lens](https://YOURNAME.github.io/lens-site/about.html)** — what Lens does, how it works, and how to get started.
- **[Privacy Policy](https://YOURNAME.github.io/lens-site/privacy.html)** — how Lens handles your data (short version: it collects nothing).

> Replace `YOURNAME` in the links above with your GitHub username once Pages is live.

## Hosting

These pages are served via GitHub Pages from this repository.

To enable: **Settings → Pages → Source**, select the `main` branch and the root (`/`) folder, then save. The pages go live at `https://YOURNAME.github.io/lens-site/` within a minute or two.

After it's live, open the privacy URL in a private/incognito window to confirm it's publicly reachable without login — the Chrome Web Store review team accesses it anonymously.

## Files

| File | Purpose |
|------|---------|
| `about.html` | Landing / about page for Lens |
| `privacy.html` | Privacy policy (linked from the Chrome Web Store listing) |

## About Lens

- **Version:** 1.5.0
- **Providers:** Google (Gemini), OpenAI, Anthropic — bring your own API key
- **Contact:** shivamgupta5203@gmail.com

## License

© 2026 Shivam Gupta. All rights reserved. These pages are published for informational purposes; the Lens name and content are not licensed for reuse.
