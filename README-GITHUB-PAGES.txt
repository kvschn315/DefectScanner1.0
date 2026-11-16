# Defect Scanner – GitHub Pages Paket

## Veröffentlichung direkt am Smartphone
1. Öffne dein Repository auf GitHub.
2. Öffne **Add file → Upload files**.
3. Lade ALLE Dateien aus diesem ZIP hoch. Wichtig: `index.html`, `app.js`, `styles.css`, `manifest.webmanifest`, `sw.js`, `icon.svg` und `.nojekyll` müssen direkt im Hauptverzeichnis des Repositorys liegen – nicht in einem zusätzlichen Unterordner.
4. Wähle **Commit changes**.
5. Öffne **Settings → Pages**. Unter Build and deployment: **Deploy from a branch**, Branch `main`, Ordner `/(root)`, dann Save.
6. Warte auf den erfolgreichen grünen Haken in **Actions → Pages build and deployment**.
7. Die Adresse lautet `https://kvschn315.github.io/defect-scanner/`, sofern das Repository tatsächlich `defect-scanner` heißt.

## Datenschutz
Die statischen App-Dateien werden über GitHub Pages ausgeliefert. Die in der App aufgenommenen/ausgewählten Bilder und Annotationen speichert die App lokal im Browser via IndexedDB. Der Code enthält keine Bild-Upload-Funktion und keine externe Analyse-API. Lokale Daten werden nicht zwischen iPhone und Android synchronisiert. Der App-Code selbst ist bei einer öffentlichen Pages-Seite öffentlich einsehbar.

## Grenzen
Dies ist ein Bildvergleichs- und Annotation-Prototyp, keine trainierte KI und kein validiertes industrielles Prüfsystem. Pixelvergleich kann durch Perspektive, Drehung, Licht und Schatten Fehlalarme erzeugen.
