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

Linux (git)	| 	Windows
pwd			echo %cd%
cd ..			cd x
ls -l (ls -la)		dir
mkdir x			mkdir x
clear			cls
git (--help)

### nitialisierung eines Repositories
git init

## Anzeige des Ordnerinhalts
git ls -la

## Aktueller Status des Repositories (Hinzugefügte Dateien, aktuelle Commits, etc.)
git status

## Neue Datei zum (leeren) Repository hinzufügen (STRG-O; STRG-ENTER; STRG-X)
nano index.js

## Ausgabe der Datei in der CLI
cat index.js

## Dateien in die Versionsverwaltung einbinden (tracken)
git add index.js
git commit (-m)       Beschreibung der Änderung (Bugfix, Features)

## Aktuellen Status überprüfen (keine ungestagedten Änderungen mehr)
git status

## Neuen Commit hinzufügen
...

## Versionsgeschichte abrufen
git log

## Erneute Änderung an der index.js
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



# Mit Github Remote Versionskontrolle

## Neues Repo erstellen (auf GitHub)
-> git remote add origin <url>
-> git push origin master

-> git push --all origin (Alle Branches syncen)


VSCode

Commit-Hashes (Head)







