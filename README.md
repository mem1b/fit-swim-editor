# FIT Swim Editor

Korrigiert Bahnen in Schwimm-FIT-Dateien (Garmin u. a.) direkt im Browser, ohne Server und ohne Upload.

- `index.html` im Browser öffnen, FIT-Datei laden.
- Die Oberfläche startet anhand der bevorzugten Browsersprachen auf Deutsch oder Englisch (inkl. Varianten wie `de-CH` und `en-US`). Die erste unterstützte Sprache wird verwendet; ohne passende Sprache startet sie auf Englisch. Nach einer Änderung der Browsersprachen die Seite neu laden.
- Auffällige Bahnen (zu lang = mehrere Bahnen, zu kurz = Phantom-Bahn) werden markiert, mit Korrekturvorschlag.
- «Teilen» und «+ nächste» korrigieren manuell. Distanzen, Bahnen, Züge und Pace werden beim Speichern neu berechnet.
- Die korrigierte Datei danach wieder in Garmin Connect, Strava, TrainingPeaks usw. hochladen.

Testdatei: `testdata/2108010024__original_garmin.FIT.gz` (entpacken).

## English

Correct lengths in swimming FIT files (Garmin and others) locally in your browser, without a server or uploads.

- Open `index.html` in your browser and load a FIT file.
- The interface follows your browser's language preferences: the first German or English preference is used, including regional variants such as `de-CH` and `en-US`. Other languages fall back to English. Reload the page after changing your browser's language preferences.
- Review highlighted lengths and apply suggestions, or use **Split** and **+ next** to correct them manually. Distances, length counts, strokes and pace are recalculated when saving.
- Upload the corrected file to Garmin Connect, Strava, TrainingPeaks or your usual training platform.

Sample file: `testdata/2108010024__original_garmin.FIT.gz` (gzip-compressed).
