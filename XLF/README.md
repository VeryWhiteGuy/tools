# Rise XLIFF Translation Tool — Showcase

This folder is the public showcase page for the **Rise XLIFF Translation Tool**, a browser-based utility that turns Articulate Rise 360 XLIFF exports into translator-friendly Excel spreadsheets and reassembles them back into valid XLIFF for re-import.

The page is served at: **https://verywhiteguy.github.io/tools/XLF/ **

## What's in this folder

| File | Purpose |
|---|---|
| `index.html` | The public showcase / description page. This is what GitHub Pages serves. |
| `screenshots/` | Images embedded in the showcase page, in narrative order. |
| `xlf-reference.json` | Internal reference: tool framing, audience, features, screenshot captions, Gumroad-prep copy. Read this first when editing the page or drafting sales copy. |
| `README.md` | This file. |

## The tool itself

The actual `RiseXLIFF_Translation_Tool.html` is **not** in this folder. It's distributed separately via MediaFire with a one-time download password. The showcase page links to the MediaFire URL; visitors without the password can see what the tool does but cannot download it.

## Updating the page

1. Edit `index.html` directly. Keep the visual style in line with `tools/thuja/` (Fraunces + IBM Plex Sans/Mono, cream/forest/terracotta palette) so the `tools/` collection reads as one family.
2. If you change anything about the tool's framing, audience, features, or screenshot order, update `xlf-reference.json` in the same commit. Future sessions read that file as the source of truth.
3. Screenshots live in `screenshots/` and are referenced by relative path from `index.html`. New screenshots go in the same folder; update both the JSON inventory and the page.

## When the MediaFire URL is ready

Search `index.html` for the placeholder `MEDIAFIRE_URL_PLACEHOLDER` and replace with the real URL. Also update the `hosting_and_distribution.tool_file.url` field in `xlf-reference.json`.
