# Coupe &amp; Stem

Marketing website for **Coupe &amp; Stem** — a cozy, plant-filled neighborhood cocktail lounge in Monument Village, the Redlands (Grand Junction, Colorado).

A candlelit botanical lounge built for slow, unhurried hours: couches and lamplight, an easy menu of drinks done well, and Sunday mimosas.

## Tech

A single-page static site. No build step, no dependencies — just HTML, CSS, and a little vanilla JavaScript. Fonts load from Google Fonts.

```
index.html      # page markup
styles.css      # all styling (dark botanical theme)
script.js       # sticky nav, mobile menu, scroll reveals
assets/
  logo.png            # original logo (cream background)
  logo-light.png      # cream logo on transparent bg (for dark sections)
  interior.png        # lounge interior / hero image
  favicon.svg         # coupe-glass favicon
```

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch.**
3. Choose the `main` branch and the `/ (root)` folder, then **Save**.
4. The site publishes at `https://<username>.github.io/coupeandstem/` within a minute or two.

The included `.nojekyll` file tells GitHub Pages to serve the files as-is.

## Things to update before launch

- **Email** — `hello@coupeandstem.com` is a placeholder. Update the `mailto:` links in `index.html` and the footer.
- **Address** — the exact street address is intentionally left as "Monument Village, Suite B3." Fill in the full address once confirmed.
- **Social links** — the Instagram / Facebook links in the footer point to `#`. Add real URLs when the accounts exist.
- **Menu &amp; hours** — drinks and hours reflect the current concept; adjust as they firm up.

---

© Coupe &amp; Stem. Please enjoy responsibly. Must be 21+.
