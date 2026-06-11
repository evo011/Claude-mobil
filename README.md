# Mini-Arcade

Eine kleine Spiele-Website fürs iPhone — drei Mini-Games, jeweils eine einzige HTML-Datei, ohne Dependencies und Build-Tools.

## Die Spiele

| Spiel | Datei | Worum geht's |
|---|---|---|
| 🐤 **Flappy Tap** | `flappy.html` | Flappy-Bird-Clone: tippe, um zu fliegen, weich den Rohren aus |
| 🧠 **Emoji-Memory** | `memory.html` | Finde alle 8 Emoji-Paare auf Zeit |
| ⚡️ **Blitz-Reaktion** | `reaction.html` | Warte auf Grün, tippe so schnell du kannst — 5 Runden, Durchschnitt zählt |

`index.html` ist die Arcade-Startseite mit funkelndem Sternenhimmel und deinen High-Scores.

## Features
- Mobile-first: Ein-Tap-Steuerung, Safe-Area-Support (Notch / Home-Indicator), Haptic Feedback
- Funktioniert auch am Desktop (Maus / Leertaste)
- High-Scores persistieren via `localStorage` und erscheinen auf der Startseite
- Keine Dependencies, keine Build-Tools — einfach öffnen und spielen

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
