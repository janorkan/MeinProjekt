# Readme zur Teilprüfung 1 GitHub

## a) GitHub Repository Setup:
- GitHub-Konto war bereits vor dem Kurs vorhanden, da es bereits für einige kleinere Kollaborationen benötigt wurde
- Neues Repository "MeinProjekt" erstellt über Klick auf "+ New" und Eingabe eines Projektnamens, Projekt auf Privat gesetzt
- ssh Pfad kopiert für Git Bash

## b) SSH-Schlüssel erstellen:
- Git Bash geöffnet und geprüft ob ssh-Key vorhanden (Screenshot b1)
- SSh Key schon vorhanden, da parallel zum Übungsscript angelegt. Ich habe parallel alle Punkte mitgearbeitet auf der Gitbash während dem Lesen des Scriptes.

## c) Lokales Repository einrichten

### 1. Konfiguration
- in das lokale Git Verzeichnis gewechselt um dort den neuen Projekt-Ordner herunterzuladen (Screenshot c1)
- vor dem "git clone" habe ich noch den SSH Agent eingerichtet, wie im Script beschrieben, um die SSH Verbindung mit Github herzustellen (Screenshot c2)
- mit "git clone" und dem GitHub Pfad das leere Repository geklont und in das Verzeichnis gewechslet (Screenshot c3 & c4)
- User Configuration mit Name und Email angelegt (Screeenshot c5)

### 2. Erster Commit
- via Bash eine neue Python-Datei erstellt mit leerem Inhalt (Screenshot c6)
- neue Datei auf staging verschoben und danach committed (Screenshot c7)

### 3. neuer Feature Branch
- neuen Branch angelegt und ausgecheckt mit "checkout -b" (Screeenshot c8)
- neuen Unterordner mit einer neuen leeren Python-Datei via Bash erstellt (Screenshot c9)
- danach leider erst einmal vergessen zu committen und direkt die main-Datei bearbeitet, das habe ich dann wieder rückgängig gemacht vor dem Commit und dann erst den Commit ausgeführt (Screenshot c10)
- danach habe ich noch die Main.py Datei bearbeitet über die Bash und eine neue Zeile/Kommentar hinzugefügt und diese Änderung dann wieder auf das Staging geschoben und committet (Screenshot c11)

### 4. Merge-Konflikt vorbereiten
- Um einen Merge-Konflikt vorzuberieten muss in mehreren Branchen die gleiche Datei an einer gleichen/ähnlichen Stelle verändetr werden, dies wurde in den näcshten Schritten mit der main.py Datei gemacht
- als erstes bin ich auf den main (nicht master) branch gewechselt, da GitHub nicht mehr Master sondern den politisch-korrekten Begiff Main verwendet
- hier habe ich die main.py auch um eine Kommentar-zeile ergänzt, und committet (Screenshot c12

### 5. Merge-Konflikt
- durch den Merge von feature auf main kam es wie gpelant zu einem merge Konflikt
- dieser wurde im Editor von mir angeschaut und manuell gelöst (beide Kommentare untereinander behalten und die Merge-Konflikt Zeilen gelöscht) (Screenshot c13)
- danach konnte die bereinigte main.py Datei committet werden, der Git log mit den Commits ist auch zu sehen im Screenshot c14 

### 6. Abschluss
- zu guter letzt habe ich das lokale Repository auf GitHub gepusht und dort zur Verfügung gestellt
- hierfür musste ich noch einen weiteren Commit machen, um die Readme und die Screenshots ins Repository aufzunehmen.
- Danke für die realitätsnahe Prüfungsaufgabe! :)
