# Sevworks Website

The marketing site for **Sevworks**, a Texas-based software development studio.

It's a plain static site (HTML, CSS and a little JS) with no build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
# or
python -m http.server 8000
```

## Files

- `index.html`: home page (hero, work, services, about, contact)
- `good-beta.html`, `kids-game-central.html`: one page per app
- `styles.css`: all styles (dark theme, responsive)
- `main.js`: mobile nav, header scroll state, footer year
- `assets/`: logos (`logo-dark.png`, `logo-light.png`, `mark.png`) and `favicon.png`

## TODO before launch

- [ ] On each app page: set the real download/play link, add screenshots, replace the `TODO` copy
- [ ] Set the real contact email (currently `hello@sevworks.com`)
- [ ] Register a domain and deploy (GitHub Pages, Netlify or Cloudflare Pages all work)
- [ ] Update the footer to "Sevworks LLC" once the LLC is formed
