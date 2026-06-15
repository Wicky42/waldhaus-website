# Waldhaus — Webseite & Admin-Dashboard

Abgeschiedene Waldhäuser für Menschen, die das Wesentliche suchen.

## Projektstruktur

```
/
├── index.html        → Kundenansicht (Waldhaus-Website)
├── admin.html        → Admin-Dashboard (Betreiber-Bereich)
└── README.md
```

## Live-Demo

🌲 **Kundenansicht:** [https://YOUR-USERNAME.github.io/waldhaus](https://YOUR-USERNAME.github.io/waldhaus)  
🔐 **Admin-Dashboard:** [https://YOUR-USERNAME.github.io/waldhaus/admin.html](https://YOUR-USERNAME.github.io/waldhaus/admin.html)

Admin-Login: `admin` / `waldhaus2026`

## Features

### Kundenansicht
- Scroll-Animationen & Parallax
- Buchungsformular mit Haus-Auswahl, Kalender, Galerie
- Leistungsübersicht je Haus
- Direkte Anbindung ans Admin-Backend (via localStorage)

### Admin-Dashboard
- **Buchungsanfragen** — Status-Workflow (Neu → Bestätigt → Archiviert)
- **Kalender** — Belegungsübersicht je Haus, farbkodiert
- **Statistiken** — Umsatz, Auslastung, Anfragenvolumen (Chart.js)
- **Abrechnung** — Rechnungsübersicht, MwSt.-Ausweisung, DATEV-Export
- Live-Sync: Formular-Einreichungen erscheinen automatisch im Admin

## Technologie

Reines HTML/CSS/JS — kein Build-Schritt, kein Backend, keine Dependencies außer:
- [Google Fonts](https://fonts.google.com) (Playfair Display, Inter)
- [Chart.js](https://www.chartjs.org) (CDN, nur Admin)

Datenpersistenz über `localStorage` (Demo-Modus).

## Lokale Entwicklung

Einfach `index.html` im Browser öffnen — oder mit einem lokalen Server:

```bash
npx serve .
# oder
python3 -m http.server 8080
```

## GitHub Pages Setup

1. Repository auf GitHub erstellen
2. Diesen Ordner pushen
3. Unter **Settings → Pages → Source:** `main` Branch, `/ (root)` auswählen
4. Nach ~60 Sekunden ist die Seite live

---

*Fiktives Projekt zu Demonstrationszwecken.*
