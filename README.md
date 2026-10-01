# bkt — Bündnis Kevin Teller

Statische Website für **bkt.lokro.dev** — _wir wollen etwas bewegen._

- `index.html` — die komplette BKT-Seite (ehemals `random.html` aus `loekro`)
- `styles/` — `style.css`, `glass.css`, `starsbg.css`
- `scripts/` — `particles.js` (rote Partikel im Wahlprogramm-Bereich)
- `assets/` — `bkt.png` (Logo: Nav, Hero, Footer, Favicon)
- `CNAME` — Custom Domain für GitHub Pages

## Lokal ansehen

Einfach `index.html` im Browser öffnen oder z. B.:

```bash
python3 -m http.server -d /tmp/opencode/bkt-new 8000
```

## Deploy

GitHub Pages, Branch `main`, Root (`/`), Custom Domain `bkt.lokro.dev`.
DNS: `bkt.lokro.dev` → CNAME → `Lokrogaming.github.io` (bereits gesetzt).
