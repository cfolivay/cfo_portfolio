# cfo_portfolio

Freelance portfolio of Cha Olivay: Shopify, landing pages and practical automation.

Plain HTML/CSS/JS with no build step and no dependencies other than Google Fonts.

```
index.html              Homepage
dental.html             Case study: dental clinic follow-up automation (demo)
assets/css/site.css     Shared styles (tokens at the top)
assets/js/site.js       Shared behaviour: header, mobile menu, scroll reveal
assets/img/<project>/   Screenshots per case study (.webp)
```

To add a case study, copy `dental.html`, swap the content and images, then link it from the
matching demo card in `index.html`.

## Publish free on GitHub Pages

1. Commit and push `index.html` to the `main` branch.
2. On GitHub, open the repo → **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Pick **Branch: `main`**, folder **`/ (root)`**, then **Save**.
5. Wait 1–2 minutes. The site goes live at `https://<your-username>.github.io/cfo_portfolio/`.

## Before sharing with clients

- When a demo case study is ready, change its "Case study coming soon" button to a real link.

## Editing

All colours, font sizes and spacing live in the `:root` block at the top of `assets/css/site.css`.
Change a token there and the whole page updates.
