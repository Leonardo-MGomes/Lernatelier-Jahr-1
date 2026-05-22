# Lernperiode 4

## Planungen
### 22.05.26
#### Planung
- An MoodleDownloader weiter arbeiten
  - Moodle Mobile HTTP requests analysieren
  - Moodle Mobile PoC mit zugriff auf folgende Daten erstellen
    - Login
    - Course info
    - User info

#### Reflexion
Heute habe ich hauptsächlich recherchiert als gearbeitet. Ich musste herausfinden wie ich die HTTP requests analysiere, zuerst dachte ich dass den Code open-source wäre, dies war aber nicht so.
Dann nutzte ich ein programm namens Man-in-the-Middle Proxy um die requests von mein handy auf mein PC lesen zu können. Ich fand die meisten funktionien die ich brauchte.
Den PoC könnte ich auch einigermassen schreiben, es gibt ein bug mit den authorization (warscheinlich werden die cookies automatisch gelöscht, bin mich aber unsicher) den ich noch beheben muss.
Nachdem ich diesen bug behebe werde ich es warscheinlich in mein Projekt [MoodleDownloader](https://github.com/Leonardo-MGomes/MoodleDownloader) implementieren.

---

### 29.05.26
#### Planung
- Authorization bug beheben
- Moodle Mobile HTTP requests in MoodleDownloader implementieren
  - Login
  - Course info
