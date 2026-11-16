# spicci2026.github.io

Dominio principale di [Spicci](https://spicci2026.github.io/spicci/).

- `index.html` rimanda all'app in `/spicci/` (repository `spicci2026/spicci`).
- `.well-known/assetlinks.json` collega l'app Android `it.spicci.app` al sito, così si apre a schermo intero senza barra degli indirizzi. Contiene l'impronta della chiave di caricamento; quando Google Play firma l'app va aggiunta anche l'impronta della chiave di firma di Google (Play Console → Integrità dell'app).
- `google6abdb31572b72c8b.html` verifica la proprietà del sito in Google Search Console (account Google del titolare) ed è collegata al sito web dichiarato in Google Play Console: **non rimuoverlo**.
- `robots.txt` indica la sitemap `https://spicci2026.github.io/spicci/sitemap.xml` (inviata a Search Console il 16/11/2026).
