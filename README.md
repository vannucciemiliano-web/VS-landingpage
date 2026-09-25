# vanitystays.it — landing page

Sito statico (HTML/CSS/JS), nessuna build necessaria.

## Struttura
- `index.html` — landing
- `privacy.html` — informativa privacy
- `img/` immagini (+ `og-cover.jpg` per l'anteprima social, favicon)
- `fonts/` Schnyder (licenza web) e Archivo, self-hosted
- `video/` video hero desktop (16:9) e mobile (9:16)
- `_headers` cache e header di sicurezza per Cloudflare Pages
- `robots.txt`, `sitemap.xml`, `favicon.ico`

## Cloudflare Pages
- Framework preset: **None**
- Build command: *(vuoto)*
- Build output directory: `/`
- Production branch: `main`

Ogni push su `main` ripubblica il sito in automatico.

## Form contatti
Web3Forms → info@vanitystays.it (access key nel form di `index.html`).
