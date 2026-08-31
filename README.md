# immomind.io

Statische Marketing-Website von ImmoMind, gehostet über GitHub Pages.

| | |
|---|---|
| Live | https://immomind.io |
| Quelle | Branch `main`, Verzeichnis `/` |
| Betreiber | IntegraMind Solutions GmbH |

## Struktur

```
index.html              Startseite
style.css               Styles
icons/                  Favicons und Logo
impressum/impressum.html
datenschutz/datenschutz.html
CNAME                   Custom Domain für GitHub Pages
.nojekyll               deaktiviert die Jekyll-Verarbeitung
```

## Deployment

Jeder Push auf `main` veröffentlicht die Seite automatisch. Kein Build-Schritt.

```bash
git add . && git commit -m "..." && git push
```

## Lokal ansehen

```bash
python3 -m http.server 8000
```

Die Ordner `linkedin/` und `facebook/` enthalten internes Marketing-Arbeitsmaterial und sind per `.gitignore` ausgeschlossen.
