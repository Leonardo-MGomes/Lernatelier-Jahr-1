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
- [X] Powershell LB-Projekt
  - [X] Funktion um Dateien in Downloads zur richtigen Ordner verschieben
  - [X] Funktion um Dateien zu herunterladen
  - [ ] Funktion um Dateien abhängig von Ordnernamen zu herunterladen (missing files zb.)
  - [ ] Scheduled task compatibility
- [ ] Schulplanner
  - [X] Mögliche Backend-Services recherchieren
  - [-] Next.js & React lernen

Ich hatte Probleme mit meinem Submodule für den PowerShell Skript, ich konnte irgendwie nicht bei Moodle einloggen. Der Grund war meine Veränderung des Codes von MoodleDownloader vor ~2 Wochen, ich habe neue Parameter hinzugefügt und andere gewechselt und in diesem Projekt noch nicht aktualisiert. Das hat mir die meiste Zeit gekostet.
Ich mache den Schulplanner mit einem Mitschüler, Bartosz, wir haben vor allem recherchiert, welche mögliche Backend Services wir nutzen können, endgültig sind wir auf folgende Optionen geblieben: Firebase, Supabase und eigener Server (oder Schul/Makerspace Server).

### Planung 19.06.2026
- [ ] MoodleChores (Powershell LB-Projekt)
  - [X] Authentifizierung Code refaktorisieren
  - [X] Main Code in InfoGather refaktorisieren
  - [X] Indexierung implementieren
  - [-] Kurs syncro implementieren
  - [ ] LB Dokumentation schreiben
- [ ] Portfolio Website (HTML & CSS LB-Projekt)
  - [X] Bookmarks erstellen 
  - [X] Mobile ansicht korrigieren
  - [X] Falls erlaubt, JS nutzen um die Bookmarks zu erstellen

Heute habe ich nicht an mein Projekt gearbeitet, weil ich in ein bisschen Zeitstress bin, Modulabgaben sind nächste Woche und ich bin noch nicht ganz bereit.
Heute war aber ansonsten ziemlich ereignislos, keine Probleme, aber viel Fleißarbeit, die ich lieber nicht gemacht hätte.
Nächstes Mal muss ich halt jede Woche ein bisschen arbeiten, anstatt alles für die letzte Woche lassen.

### Planung 26.06.2026
- [ ] MoodleDownloader
  - [ ] Scraper logik muss Kurse mit dependencies erlauben
  - [ ] Datenbank auch ändern um dies zu erlauben
- [ ] Schulplanner
  - [ ] Next.js & React lernen
  - [ ] PoC: Erste gedanken zur Projekt machen (aka weiterhin planen)
  - [ ] PoC: Simples HTML frontend schreiben
  - [ ] PoC: Datenbank schema erste gedanken
  - [ ] PoC: Datenbank schema implementieren
