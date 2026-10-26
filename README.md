# Folio

Studien-App für den Mac: Notizen und Datenbanken wie in Notion, auf PDFs schreiben wie in GoodNotes, Folien mit Notizblatt daneben, verbundene Finder-Ordner und Claude als Lernhilfe.

## Herunterladen

Unter **[Releases](../../releases/latest)** die Datei `Folio-0.9.0.dmg` laden.

Voraussetzung: Mac mit Apple-Chip (M1 oder neuer).

## Installieren

1. Die `.dmg` öffnen und Folio in den Ordner „Programme“ ziehen.
2. Folio einmal öffnen. macOS warnt, weil die App nicht bei Apple registriert ist.
3. „Systemeinstellungen“ → „Datenschutz & Sicherheit“ → ganz unten **„Trotzdem öffnen“**.

Meldet macOS „Folio ist beschädigt“, im Terminal einmal ausführen:

```
xattr -cr /Applications/Folio.app
```

## Hinweise

- Deine Notizen und PDFs bleiben auf deinem Mac in einem Ordner, den du selbst wählst.
- Für Claude direkt in Folio brauchst du einen eigenen API-Schlüssel; der Anschluss an die Claude-Desktop-App funktioniert mit deinem Abo.
- PowerPoint-Dateien zeigt Folio nur an, wenn Keynote oder LibreOffice installiert ist.
