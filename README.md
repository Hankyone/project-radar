# Project Radar

One-page project tracker.

This repo is meant to be updated from a pinned ChatGPT thread. The page reads `projects.json` and renders project cards grouped by status, priority, and freshness.

## Files

- `index.html`, static single-page tracker
- `projects.json`, project state
- `changelog.md`, dated change history
- `CNAME`, custom domain for `projects.anouar.ca`
- `.nojekyll`, keeps GitHub Pages simple

## Scope

This tracker is not a repo audit and does not inspect or expose repository contents.

Each project entry should be limited to:

- project name
- one-line description
- status
- priority
- last touched date
- next action
- blocker, only when safe to share
- links, only when intentionally shared

Sensitive project work can still be represented by a sanitized project name and generic one-liner. Keep private details and internal notes out of this repo.

## Update model

1. Drop a natural-language update in the pinned chat.
2. The assistant updates `projects.json`.
3. The assistant appends to `changelog.md`.
4. `index.html` only changes when the tracker UI changes.

## GitHub Pages

This repo is configured for the custom domain:

`https://projects.anouar.ca/`

Pages source:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/root`
