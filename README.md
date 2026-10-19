# Handklang

Musik mit den Händen spielen: ein Gesten-Synthesizer, der komplett im Browser läuft.
Die linke Hand wählt den Akkord, die rechte Hand steuert Lautstärke und Klangfarbe.
Das Kamerabild wird nur auf dem eigenen Gerät verarbeitet.

## Funktionen

- Drei Modi: Akkorde, Melodie, Theremin
- Alle 12 Tonarten, Dur/Moll fest oder per Handgelenk
- Neun Akkordtypen, Arpeggiator, Auto-Bass
- Spielen ohne Kamera über Tasten 1–7 oder Touch-Pads
- Aufnahme bis 2 Minuten als Video oder Ton

## Aufbau

| Pfad | Inhalt |
| --- | --- |
| `index.html` | Die App |
| `vendor/mediapipe/` | Handerkennung (MediaPipe Tasks Vision 0.10.14) |
| `fonts/` | Schriften, lokal eingebunden |
| `models/` | Handerkennungs-Modell, wird beim Veröffentlichen automatisch geladen |
| `.github/workflows/pages.yml` | Veröffentlicht die Seite auf GitHub Pages |

Alle Dateien werden von derselben Adresse ausgeliefert. Es gibt keine Anfragen an Google Fonts, CDNs oder andere Dritte.

## Veröffentlichen

1. Unter **Settings → Pages → Build and deployment → Source** „GitHub Actions“ wählen.
2. Jeder Push auf `main` veröffentlicht die Seite neu.

## Lizenzen

Drittkomponenten und ihre Lizenzen stehen in `lizenzen.html` und im Ordner `licenses/`.
