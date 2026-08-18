# syntropia.fi

Syntropian julkinen kotisivu. Staattinen: ei kehyksiä, ei riippuvuuksia,
ei ulkoisia latauksia (fontit, analytiikka, CDN).

- `index.html`, `style.css`
- `assets/` — logo, logosta leikattu wordmark, faviconit
- `CNAME` — GitHub Pages -custom domain

Paikallinen esikatselu:

    python3 -m http.server 8541 --directory .
