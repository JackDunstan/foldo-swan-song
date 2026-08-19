# foldo-swan-song

**SWT101 — Swans with towels**, a one-page parody nanocredential from
*IOU*: fold one (1) hotel towel into one (1) swan, across six folds,
self-assessed and unmoderated. Accredited by no one.

A single static `index.html` — no build step, no dependencies.

## What's on the page

- **Unit overview** — course facts, and Foldo, the unit mascot
- **Lecture 1 — Demonstration** — an embedded (muted) video walkthrough
- **The six folds** — the fold-by-fold competency checklist
- **Certified Swan Practitioner** — a certificate of completion

## Running locally

It's a plain HTML file — open it directly, or serve the folder so
relative assets (`foldo.jpg`) load correctly:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

| File        | Purpose                              |
|-------------|---------------------------------------|
| `index.html`| The entire page — markup, styles, script |
| `foldo.jpg` | Foldo, the unit mascot                |
