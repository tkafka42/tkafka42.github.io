# Talha Yigit – portfolio

My personal portfolio site, built as a terminal-style page. Plain HTML and CSS, no framework, no build step, no trackers.

**Live:** https://tkafka42.github.io/

## Files

| File | Purpose |
| --- | --- |
| `index.html` | All content |
| `style.css` | Styling (dark theme, monospace, purple/green accents) |
| `robots.txt` | Allows crawlers |

Project images are loaded from the `dotfiles` and `scara-chess` repos on `raw.githubusercontent.com`. Fonts (JetBrains Mono) come from Google Fonts. Nothing else is loaded from outside.

## Run locally

```sh
python -m http.server 8000
```

Then open http://localhost:8000.

## Publish

Pushing to `main` deploys via GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root). For the `https://tkafka42.github.io/` address the repo must be named `tkafka42.github.io`.

## Contact

GitHub: [@tkafka42](https://github.com/tkafka42)
