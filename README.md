# Die Geschichte des 👨‍💻 Programmierers

Dies ist eine einfache HTML-Seite, die die humorvolle Geschichte eines Programmierers erzählt und gleichzeitig eine wichtige Botschaft über das Speichern von Programmen vermittelt. Die Seite enthält auch ein interaktives Element, einen Schalter, der mit einer JavaScript-Funktion verknüpft ist.

## Inhalt

### HTML
- `index.html`: Die Hauptdatei der Webseite.
  - `<!DOCTYPE html>`: Deklaration des HTML-Typs.
  - `<html lang="de">`: Definition der Sprache als Deutsch.
  - Metadaten wie Titel, Zeichensatz, und Ansichtsparameter.
  - Einbindung von Favicon und Stylesheet (`./img/digi-world.ico` und `./style.css`).
  - Der Hauptinhalt befindet sich im `<body>`-Tag.

### Inhalt
- Ein div-Container mit der ID "card" enthält den Hauptinhalt der Seite.
  - Ein weiteres div mit der ID "poem" enthält das Gedicht über den Programmierer.
  - Am Ende des Gedichts befindet sich ein Schalter (`<label class="switch">`), der mit einem Checkbox-Input verbunden ist.
  - Der Schalter hat eine Schaltfläche (`<div class="button" id="btnSave" onclick="DontForgetToSaveYourBeautifulProgram(/*😀*/)">`), die mit einer JavaScript-Funktion (`DontForgetToSaveYourBeautifulProgram`) verknüpft ist.

### JavaScript
- `script`-Tag enthält eine einfache JavaScript-Funktion `DontForgetToSaveYourBeautifulProgram`, die beim Klicken auf die Schaltfläche einen Alarm mit der Meldung "Vergiss nicht zu speichern!" auslöst.

## Verwendung
1. Lade alle Dateien (HTML, CSS, Favicon) in dasselbe Verzeichnis herunter.
2. Öffne `index.html` in einem Webbrowser.

## Anpassung
- Du kannst den Text des Gedichts ändern, um die Geschichte zu personalisieren.
- Das Favicon (`./img/digi-world.ico`) kann durch ein eigenes ersetzt werden.
- Das Stylesheet (`./style.css`) kann angepasst werden, um das Erscheinungsbild der Seite zu ändern.

## Beitrag
Wenn du Ideen zur Verbesserung oder Erweiterung der Seite hast, freue ich mich über Beiträge und Pull-Anfragen.

Viel Spaß beim Erzählen der Geschichte des Programmierers! 😄
