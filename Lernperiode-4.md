# Lern-Periode 4

- Name: Leonardo Miranda Gomes
- Zeitraum: 24.04.2026 bis 26.06.2026

## Grob-Planung

### Noten

### Veränderungen

### Projekte / neue Technologien

### Generelle Ziele

## Tagesplanungen

### Planung 22.05.2026
- An MoodleDownloader weiter arbeiten
  - [X] Moodle Mobile HTTP requests analysieren
  - [X] Moodle Mobile PoC mit zugriff auf folgende Daten erstellen
    - [X] Login
    - [X] Course info
    - [X] User info

Heute habe ich hauptsächlich recherchiert anstatt gearbeitet. Ich musste herausfinden wie ich die HTTP requests analysiere, zuerst dachte ich dass den Code open-source wäre, dies war aber nicht so.
Dann nutzte ich ein programm namens Man-in-the-Middle Proxy um die requests von mein handy auf mein PC lesen zu können. Ich fand die meisten funktionien die ich brauchte.
Den PoC könnte ich auch einigermassen schreiben, es gibt ein bug mit den authorization (wahrscheinlich werden die cookies automatisch gelöscht, bin mich aber unsicher) den ich noch beheben muss.
Nachdem ich diesen bug behebe werde ich es wahrscheinlich in mein Projekt [MoodleDownloader](https://github.com/Leonardo-MGomes/MoodleDownloader) implementieren.

### Planung 29.05.2026
- [x] Authorization bug beheben
- [ ] Moodle Mobile HTTP requests in MoodleDownloader implementieren
  - [ ] Login
  - [ ] Course info

Ich konnte den Authorization bug ziemlich einfach beheben, es waren session cookies die ich ausversehen gelöscht habe.
Leider konnte ich die Moodle Mobile API nicht implementieren, den grund dafür war dass die Schule die Requests blockiert und ich sie daher nicht nachschreiben kann. Im nachhinein sollte ich die Endpoints dokumentiert haben, leider tat ich es nicht und kann jetzt nicht weiterarbeiten.
Ich habe anstatt den [MoodleDownloader](https://github.com/Leonardo-MGomes/MoodleDownloader) an mein LB Powershell Projekt.

### Planung 05.06.2026
- [-] Planung bearbeiten um die Anforderungen zu erfülen
- [ ] Powershell LB-Projekt
  - [X] In Moodle einloggen und session cookies speichern
  - [X] Session cookies und password encrypten
  - [X] Username, password und session cookies in eine datei speichern
  - [X] Funktion zum testen von session cookies (valid oder neuen holen)
  - [ ] Funktion um Dateien in Downloads zur richtigen Ordner verschieben
  - [ ] Funktion um Dateien zu herunterladen

Heute war es ziemlich ereignislos, ich hatte nirgendswo problemen.
Ich habe diesen Lernperiode dokument bearbeitet um die meisten anforderungen zu erfüllen, ich habe jedoch den Grobplanung noch nicht gemacht, also muss ich es noch machen, wahrscheinlich nächster woche.

### Planung 12.06.2026
- [ ] Planung bearbeiten um die Anforderungen zu erfülen
- [ ] Powershell LB-Projekt
  - [ ] Funktion um Dateien in Downloads zur richtigen Ordner verschieben
  - [ ] Funktion um Dateien zu herunterladen
  - [ ] Funktion um Dateien abhängig von Ordnernamen zu herunterladen (missing files zb.)
  - [ ] Scheduled task compatability
  