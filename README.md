# eso-website-assets

Skripte, Bildfolgen und Filme für www.eso-anlage.de, ausgeliefert über jsDelivr.

- `eso.min.js` – Seitenskript (Menü, Animationen, Rechner, Darstellung der Anlage), minifiziert
- `eso-web.css` – Zusatz-CSS (Nachfahren-Regeln, Zustände, Animationen)
- `hero3d.js` – interaktive 3D-Darstellung der ESO-Anlage (enthält three.js, MIT-Lizenz); Kopie unter `anlage/hero3d.js`, von `eso.min.js` geladen
- `anlage/` – Bildfolgen der Anlage (`drehung/`, `explosion/`, `explosion-1000/`) und `explosion/anker.js`
- `film/` – Filme und Standbilder

Einbindung mit fester Version:

```html
<script src="https://cdn.jsdelivr.net/gh/kevinpxm/eso-website-assets@v1.2.1/eso.min.js" defer></script>
```

Lizenzhinweis: `hero3d.js` enthält three.js (MIT-Lizenz, © three.js authors).
