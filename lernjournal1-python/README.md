# Lernjournal 1 Python

## Repository und Library

| | Bitte ausfüllen |
| -------- | ------- |
| Repository (URL)  | https://github.com/DEIN_USERNAME/flashcard-app |
| Kurze Beschreibung der App-Funktion | Flashcard-App mit Add/Delete/Flip-Funktionalität, Carousel-Effekt mit Sneak-Peek |
| Verwendete Library aus PyPi (Name) | keine |
| Verwendete Library aus PyPi (URL) | keine |
| ... | |
| ... | |

## App, Funktionalität
Die Applikation erlaubt es dem User, Lernkarten (Flashcards) zu erstellen, zu durchsuchen und zu üben. Die Karten werden auf der Seite als Carousel angezeigt – mit einer aktiven Karte in der Mitte und einer Vorschau der vorherigen/nächsten Karte.

#### Ansicht im Web-UI:
!!!!! ERGÄNZEN (Screenshot der Hauptansicht mit Carousel) !!!!!

### Funktionen Karten bearbeiten
Der User kann eine neue Karte über ein Modal hinzufügen (mit Eingabe von Vorder- und Rückseite) oder bestehende Karten über die Seitenleiste löschen.

#### Ansicht im Web-UI:

!!!!! ERGÄNZEN (Screenshot Modal + Seitenleiste mit Kartenliste) !!!!!

#### Code der Applikation:

!!!!! ERGÄNZEN (Screenshot der `app.py` Flask-Routen oder JS-Rendering) !!!!!

### Flashcard Viewer mit Analyse-Funktion *(optional)*
Aktuell enthält die App keine Textanalyse, kann aber mit einer Library wie `textblob` oder eigener Logik um Wortanzahl, Palindrome etc. erweitert werden.

## Dependency Management

Da keine externen Libraries verwendet werden (reines Flask + HTML/JS), enthält das Projekt ein minimales `requirements.in`:

### Beispiel `requirements.in`:
```text
flask
