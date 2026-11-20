# Cascade Solar + Air — Finance Operations

An interactive, single-page prototype of a finance-operations console for a
residential solar + HVAC services company. It is a self-contained static web
app — no build step and no dependencies to install.

## Live demo

After GitHub Pages is enabled for this repository, the site is live at the URL
shown under **Settings → Pages** (GitHub prints "Your site is live at …"):

```
https://kadeemhaughton.github.io/Solar-HVAC/
```

## What's here

- `index.html` — the complete prototype; all styles and scripts are inline.
- Light and dark themes — toggle in the UI; the choice is remembered per browser.
- Web fonts (Inter, Sora, IBM Plex Mono) are loaded from Google Fonts.
- `.nojekyll` — tells GitHub Pages to serve the files as-is.

## Running it locally

No build or dependencies. Either open `index.html` directly in a browser, or
serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
