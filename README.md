# HR Announcement Poster Generator

A no-code, browser-based generator for **Systems Notice** HR announcement posters
(INFOSOFT · ACCELTECH · KASSATECH · DIMENSIONS). Fill in the fields, pick a size,
and export a print-ready PNG.

## Features

- **Presets** — Timekeeping Cut-off Reminder, Holiday Announcement, Payruler/HRIS Advisory, Memorandum, or Blank.
- **Sizes** — 1200×1200 square, 1200×1700 portrait (official), plus 1080×1080 IG post, 1080×1920 story, 1200×628 banner.
- **Selectable logos** — choose which of the four company logos appear (fixed order, upper-right).
- **Inline emphasis markup** in any text field:
  - `**bold**` → bold near-black
  - `[[red]]` → urgent (use once per poster)
  - `{{blue}}` → informational italic
  - `((green))` → positive / ongoing
- **WYSIWYG body** — line breaks render exactly as typed; each blank line = one line of space.
- **Multi-line terminal panel** — put each date/URL/status on its own line and they stack.
- **PNG export** at 2× resolution for crisp printing.

## How it works

Everything runs client-side in the browser. Fonts (Instrument Sans, JetBrains Mono)
and the company logos are embedded in the file, so it works fully offline with no
external requests, no data collection, and no storage.

## Usage

Open `index.html` in any modern browser — or visit the GitHub Pages URL once deployed.

## Deployment (GitHub Pages)

1. Push these files to a repository (root of the repo).
2. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)`. Save.
4. The site publishes at `https://<username>.github.io/<repo>/` within a minute or two.

> **Note:** Company logos are embedded. On a **public** repo/Pages site they become
> publicly downloadable. Use a private repo (with access-controlled Pages) or internal
> hosting if that matters for your use case.

## Fonts

Instrument Sans and JetBrains Mono — both licensed under the SIL Open Font License 1.1.
