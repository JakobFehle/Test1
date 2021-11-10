# Git & Github

## Wieso Git & Github?
Versionsverwaltung, Versionskontrolle, kollaboratives Arbeiten

Git -> Lokale Versionsverwaltung
GitHub -> Cloud-Integration von Git
& Projektmanagement

## Wie Git & Github?
Cli vs Desktop Client vs VSCode vs Browser

## Git Installation

## Git -> CLI / Erfahrung Kommandozeile (CLI)?
(Rechtsklick -> Git-Bash here)

| Linux (git)    	|   	| Windows   	| Anmerkung        	|
|----------------	|---	|-----------	|------------------	|
|                	|   	|           	|                  	|
| pwd            	|   	| echo %cd% 	| Aktueller Pfad   	|
| cd ..          	|   	| cd x      	| Change Directory 	|
| mkdir          	|   	| mkdir     	| Make Directory   	|
| ls -l (ls -la) 	|   	| dir       	| Alle Ordner      	|
| clear          	|   	| cls       	| Clear CLI        	|
| git --help     	|   	|           	|                  	|

# Erstellen eines Git-Repositories
## Initialisierung eines Repositories
mkdir Git-Intro
git init

## Anzeige des Ordnerinhalts
git ls -la

## Aktueller Status des Repositories (Hinzugefügte Dateien, aktuelle Commits, etc.)
git status

## Neue Datei zum (leeren) Repository hinzufügen (STRG-O; STRG-ENTER; STRG-X)
nano index.js

## Ausgabe der Datei in der CLI
cat index.js

## Überprüfen des Git-Repositories
git status

## Dateien in die Versionsverwaltung einbinden (tracken)
git add index.js
git commit (-m)       Beschreibung der Änderung (Bugfix, Features)

## Aktuellen Status überprüfen (keine ungestagedten Änderungen mehr)
git status

## Neuen Commit hinzufügen (Refactoring)
...

## Versionsgeschichte abrufen
git log (Git Hashes)

## Erneute Änderung an der index.js (Schreibfehler)
nano index.js

## Untersuchung der Änderung und Rückgängig machen
git diff index.js

git checkout -- index.js


# Git Branches

## Alle Branches abfragen
git branch

## Neuen Branch anlegen
git branch development
git branch

## Zu neuem Branch wechseln
git checkout development

git status

## Neuen Commit erstellen (Bugfix Methodenaufruf)
nano index.js

git add . && git commit -m "Bugfix: Aufruf der HelloWorld Funktion"

## Überprüfen der Änderung in den beiden Branches
git log

git checkout master

git log

## Merge der beiden Branches

git merge development (Eventuell Konflikt)

git log

## Alten Branch löschen wenn nicht mehr benötigt
git branch -d development

# Mit Github Remote Versionskontrolle

## Neues Repo erstellen (auf GitHub)
-> git remote add origin <url>
-> git push origin master

-> git push --all origin (Alle Branches syncen)

## Repo auf Github
### Auswahl der Branches
### Hinzufügen/Ändern/Herunterladen von Dateien
Leere Datei hinzufügen
### Auswahl der Commits, Begutachten des Repos zu einem bestimmten Stand, ändern des WD zu einem bestimmten Commit
### Wiki
### Erstellen von Issues und Projects
### Pull-Request später
  
## Pull von Remote
git pull

  
# VSCode
## Projekt einbinden
## Git History (Commits, Branches, Reset, New Branch)
## Branch wechseln
## Neuen Branch mit Kommentaren
### Kommentare in Datei hinzufügen
### Änderungen Stagen
### Änderungen Commiten
### Branch mergen (sollte funktionieren)
## Neuer Branch mit Patch (Neuer Comment und neuer Text)
Stagen, Commiten und Mergen
## Merge-Konflikt lösen

  
# Github Pull-Requests (Close Issue-Nummer)
Über Pull-Requests finden Reviews statt
## Patch -> Master Mergen
Merge Conflict im Browser lösen und commiten oder in VSCode Master -> Commit mergen und commiten + pushen (Pull-Request wird dann aktualisiert)
  
# Github Desktop
  

# Beispielprojekt Mood-Game
  







