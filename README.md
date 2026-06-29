# Project Radar

Public-safe one-page project dashboard.

This repo is meant to be updated from a pinned ChatGPT thread. The dashboard reads `projects.json` and renders project cards grouped by status, priority, and freshness.

## Files

- `index.html`, static single-page dashboard
- `projects.json`, project state
- `changelog.md`, dated change history
- `.nojekyll`, keeps GitHub Pages simple

## Update model

1. Drop a natural-language update in the pinned chat.
2. The assistant updates `projects.json`.
3. The assistant appends to `changelog.md`.
4. `index.html` only changes when the dashboard UI changes.

## Public safety rules

Do not commit credentials, client names, private targets, exploit details, private revenue numbers, internal URLs, or personal identifiers.

Use short public-safe summaries. Keep sensitive context in the pinned chat or a private repo.

## GitHub Pages

Enable Pages from repository settings:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/root`

Expected URL:

`https://hankyone.github.io/project-radar/`
