# Videoschmiede

Musikvideo-Studio – komplett lokal im Browser. Verbesserte MuseGen-Vorlage.

## Was drin ist

- **index.html – VideoSchmiede:** Song + Material reinziehen → animiertes Musikvideo mit Intro/Outro und WebM-Export mit Ton.
  - **Foto-Serie-Modus:** Einzelbilder reinziehen, jedes Bild wird eine Filmszene (Ken-Burns-Kamerafahrten, weiche Blenden, Beat-Puls). Lange Songs bekommen automatisch mehrere Takes pro Bild.
  - **Visual-Stil-Modus (Neu):** Ganz ohne Bildmaterial zeichnen fünf audio-reaktive Stile – Neon-Grid, Partikel-Strom, Spektrum-Ring, Lo-Fi-Fenster, Cinematic – das Video live aus der Musik. Bass, Mitten und Höhen des Songs steuern Puls, Partikel, Regen, Licht und Platten-Drehung.
- **spalter.html – Collage-Spalter:** Collage (z. B. 4×6-Raster mit weißen Stegen) per Raster-Preset in Einzelbilder zerlegen – fertig für die VideoSchmiede. Jetzt auch als eigenes Repo: [Collage-Spalter](https://github.com/adrgrie-lgtm/Collage-Spalter).

## Workflow

1. Collage? Erst mit dem [Collage-Spalter](https://github.com/adrgrie-lgtm/Collage-Spalter) (hier: `spalter.html`) in Einzelbilder zerlegen.
2. `index.html` öffnen, Modus wählen: Foto-Serie oder Visual-Stil.
3. Musik (MP3/WAV/OGG/M4A) reinziehen, im Foto-Modus zusätzlich Einzelbilder, „Video zusammenbauen“ klicken.
4. „Video exportieren (WebM)“ – der Browser spielt das Video einmal durch und zeichnet es mit Ton auf.

Kein Server, kein Upload, kein Konto, kein Tracking – alles läuft lokal im Browser.
