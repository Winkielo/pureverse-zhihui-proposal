# 智慧禪境 · Pureverse × 西方寺 提案

Password-gated interactive proposal deck.

## Live URL

After GitHub Pages is enabled:

`https://<username>.github.io/<repo>/`

## Password

See `PASSWORD.txt` in the parent `deploy/` folder (not committed). Default: `Pureverse2026`

## Privacy note

GitHub Pages has **no server-side Basic Auth**. Protection is the on-page password gate (SHA-256). Anyone with the URL can load assets; the gate blocks casual viewing of the deck UI.

Prefer sharing the **URL and password separately**.

## Local preview

```bash
python3 -m http.server 8765
# open http://localhost:8765
```
