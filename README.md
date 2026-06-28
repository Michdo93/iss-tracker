# 🛰 ISS-Tracker

Live-Tracking der Internationalen Raumstation für GitHub Pages.

🔗 **Live:** `https://<dein-username>.github.io/iss-tracker/`

## Features
- **Live-Karte** – Leaflet.js mit CARTO Dark Tiles
- **Position** – Breitengrad, Längengrad, Höhe (~408 km), Geschwindigkeit (~27.600 km/h)
- **Orbit-Spur** – Bahn der letzten 80 Positionen als gestrichelter Pfad
- **Crew** – Aktuelle ISS-Besatzung via Open Notify API
- **Auto-Refresh** – alle 5 Sekunden
- **Follow-Modus** – Karte folgt der ISS; Drag zum Deaktivieren, `F`-Taste zum Reaktivieren
- **Fallback-API** – wheretheiss.at als primäre Quelle, Open Notify als Fallback

## APIs
- [wheretheiss.at](https://wheretheiss.at) – Position mit Geschwindigkeit und Höhe
- [api.open-notify.org](http://api.open-notify.org) – Crew + Positions-Fallback

## Deployment
```
Settings → Pages → Source: main / root
```
Kein API-Key, kein Backend, kein npm.

## Lizenz
MIT
