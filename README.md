# VideoSchmiede

Musikvideo-Studio: Einzelbilder + Song rein – fertig ist ein animiertes Musikvideo mit Kamerafahrten, weichen Blenden und Beat-Puls. Läuft komplett lokal im Browser: kein Server, kein Upload, kein Konto.

## Features
- **Einzelbild-Workflow**: jedes Bild eine Filmszene, Reihenfolge frei mischbar, einzelne Szenen per Klick entfernen
- **Ken-Burns-Kamerafahrten**, mathematisch auf die Bildgrenzen geklemmt
- **Beat-Puls & Atmung** über den Spectrum-Analyzer des Songs
- **Robuster Musik-Import**: 0-Byte-Guard für direkt aus Messenger-Apps gezogene Dateien, Workaround für MP3s ohne Dauerangabe
- **Lange Songs**: automatische Takes pro Bild; **kurze Songs**: automatische Kappung auf das, was der Song hergibt
- **Export als WebM mit Ton** (MediaRecorder, direkt aus der Vorschau)

## Nutzung
1. `index.html` im Browser öffnen (Doppelklick genügt – kein Build, keine Abhängigkeiten)
2. Einzelbilder reinziehen, Musik laden
3. „Video zusammenbauen“ → Vorschau prüfen → „Video exportieren (WebM)“

## Hinweis zu Collagen
Collagen (mehrere Panels in einem Bild) werden nicht verarbeitet – dafür ist ein eigenes Zusatz-Tool geplant, das Collagen automatisch in Einzelbilder zerlegt. Bis dahin: Panels selbst zuschneiden und die Bilder einzeln laden.
