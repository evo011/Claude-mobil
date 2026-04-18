# Flappy Tap

Ein minimalistisches Flappy-Bird-Clone — single-file HTML5-Canvas-Game, optimiert fürs iPhone.

## Features
- Ein-Tap-Steuerung (funktioniert auch mit Maus / Leertaste)
- Parallax-Wolken, Partikel-Bursts, Haptic Feedback
- Safe-Area-Support (Notch / Home-Indicator)
- High-Score persistiert via `localStorage`
- Progressiv steigende Geschwindigkeit
- Keine Dependencies, keine Build-Tools

## Lokal spielen
```bash
# Einfachster Weg: direkt im Browser öffnen
open index.html

# Oder mit einem lokalen Server (falls du iPhone im gleichen WLAN nutzen willst):
python3 -m http.server 8000
# Dann auf dem iPhone: http://<dein-rechner-ip>:8000
```

## Auf iPhone wie eine App installieren
1. URL in **Safari** öffnen
2. Teilen-Button → **Zum Home-Bildschirm**
3. Icon tippen — läuft im Vollbild ohne Browser-UI

## Steuerung
- **Tippen** (oder Leertaste / Pfeil hoch): fliegen
- Weich den Rohren aus, erreiche einen neuen High-Score

## Dateien
- `index.html` — Alles in einer Datei (HTML + CSS + JS)
