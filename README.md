# Tixxle — Website

Landing page and privacy policy for **Tixxle — Color Match Arcade**, a
game by [Gicklatt](https://gicklatt.github.io).

🔗 **Live:** [gicklatt.github.io/tixxlegame](https://gicklatt.github.io/tixxlegame)

## About the game

A fast color-match arcade game. Two characters hold their lanes, colored
blocks race in — one tap swaps the lanes. Line up the color, score the
match, chain combos that bend time. Endless Run plus 100 handcrafted
levels across four worlds, six collectible pixel characters and daily
quests — all wrapped in an Atari-era neon palette.

## Tech stack

- Plain static **HTML + CSS** — no build step
- Fonts: Press Start 2P + Inter (Google Fonts)
- Hosted on **GitHub Pages**

## Structure

| Path | Purpose |
|------|---------|
| `index.html` | Game landing page |
| `privacy/index.html` | Privacy policy (App Store / Google Play URL) |
| `assets/` | Icon (`icon.svg`) and screenshots |
| `robots.txt`, `sitemap.xml` | SEO |
| `.nojekyll` | Disables Jekyll processing |

## Develop

Open `index.html` in a browser, or serve locally:

```bash
python3 -m http.server 8000   # http://localhost:8000
```

## Deploy

GitHub Pages → **Settings → Pages → Deploy from a branch → `main` / root**.

## Store URLs

- Privacy Policy: `https://gicklatt.github.io/tixxlegame/privacy/`
- Support / Marketing: `https://gicklatt.github.io/tixxlegame/`

> Tixxle 1.0 ships with **no ads**, so it needs no `app-ads.txt`. The
> shared `app-ads.txt` lives in the
> [`gicklatt.github.io`](https://github.com/gicklatt/gicklatt.github.io)
> repo and serves ad-supported games only.

---

© Gicklatt · [gicklatt@gmail.com](mailto:gicklatt@gmail.com)
