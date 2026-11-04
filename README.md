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

## Zusatz-Tool: Collage-Spalter (`spalter.html`)
Collagen (mehrere Panels in einem Bild) zerlegt der Collage-Spalter in einzelne JPGs – Raster bis 12×12, Rand-Anteil in Prozent abschneiden (z. B. 5 % für weiße Stege), Panels einzeln an/abwählen, Speicherung in Original-Pixelgröße und Lesereihenfolge (`name_panel-01.jpg` …). Anschließend die Einzelbilder einfach in die VideoSchmiede ziehen.

**Workflow:** Collage → `spalter.html` (Raster festlegen, JPGs speichern) → `index.html` (Bilder + Musik, Video bauen)
