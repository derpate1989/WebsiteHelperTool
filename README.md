# WebsiteHelperTool

Kleines Windows-Hilfstool fuer Website-Arbeiten.

## Funktionen

- Bilder per Drag and Drop komprimieren
- Qualitaet auf 100%, 75%, 50% oder 25% setzen
- Zielordner auswaehlen, Standard ist der Windows-Bilderordner
- Bilder als JPG speichern
- Einzelne Bilder aus der Liste entfernen oder die komplette Liste leeren
- Codebloecke in einen fertigen HTML-Codeblock fuer die Website umwandeln
- Fertigen HTML-Code per Button in die Zwischenablage kopieren

## Download / EXE

Im Repository liegt die kleine Single-File-Variante:

```text
WebsiteHelperTool.exe
```

Diese Version ist bewusst klein und GitHub-freundlich. Sie setzt auf dem Ziel-PC die **.NET 8 Desktop Runtime** voraus.

Die komplett eigenstaendige Variante ohne Runtime-Abhaengigkeit ist lokal ebenfalls gebaut, aber ca. 162 MB gross und damit fuer normale GitHub-Dateien zu gross. Diese Version sollte bei Bedarf als GitHub Release-Asset hochgeladen werden.

## Lokale Build-Ausgaben

- Kleine EXE: `publish-single-small/WebsiteHelperTool.exe`
- Eigenstaendige EXE: `publish-single/WebsiteHelperTool.exe`
