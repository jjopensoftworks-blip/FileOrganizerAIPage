# FileOrganizerAI — landing page

Marketing / product page for **FileOrganizerAI**, an offline, privacy-first file
organizer for Windows.

The site is a single static page served by **GitHub Pages** from the [`docs/`](docs/)
folder.

- [`docs/index.html`](docs/index.html) — the page (Tailwind via CDN, no build step)
- `docs/.nojekyll` — tells Pages to serve the folder as-is, without Jekyll processing

## Enabling GitHub Pages

In the repo **Settings → Pages**:

1. **Source:** *Deploy from a branch*
2. **Branch:** `main` — folder **`/docs`**
3. Save. The site publishes at:

   https://jjopensoftworks-blip.github.io/FileOrganizerAIPage/

## Editing

Just edit [`docs/index.html`](docs/index.html) and push to `main` — no build,
no dependencies. Update the **Download** links (Microsoft Store URL and the direct
`.exe` release link) once those are live.
