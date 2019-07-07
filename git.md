Git Befehle:
---
---
Starte Git-Projekt
---
- Erstelle einen Ordner oder gehe in einen bereits existierenden Ordner. (Mit der Console)
- git init

Das sorgt dafür dass .git Datein im Ordner hinterlegt werden, die für die Versionierung benötigt werden.

---
Git Workflow
--- 
- Das lokale Arbeitsverzeichnis also auf dem Rechner wird als Working Directory bezeichnet
- Datein, die wird auf hochladen wollen, werden in die Staging Area gepackt.
- Datein werden von der Staging Area auf ein Repository geladen.
---
Working Directory
---
- Hier wird gearbeitet. Also Datein bearbeitet, hinzugefügt oder gelöscht.
---
Staging Area
--
- Hier werden alle Datein, die bereit sind permanent gespeichert zu werden, hinterlegt.
- Um Datein von der Staging Area zum Repository zu schicken müssen sie commited werden.
---
Repository
--
- Hier werden die Veränderungen permanent als verschiedene Versionen gespeichert.
---
Von Working Directory zur Staging Area:
- git add <file 1> <file 2>
---
Von der Staging Area zum Working Directory:
- git rm --cached <file 1>
---
Siehe den aktuellen Stand der Datein im Workflow an:
- git status
---
Siehe dir die Unterschied an:
- git diff <file 1>
---
Permanentes Speichern der Änderungen:
- git commit -m 'Message in der Gegenwart'
---
Überprüfe die letzten Commits:
- git log
---

GitHub
---
- GitHub ist eine Plattform, auf der Repositories gespeichert werden können.
- GitHub benötigt einen Account, um die Projekte zuweisen zu können.
- Auf GitHub können dann Repositories angelegt werden.
---
Lokales Repository mit dem GitHub Repository verbinden.
---
- git init
- git add .
- git commit -m 'Erster Commit'
- git remote add origin https://github.com/Jannig89/GitPractice.git
- git push -u origin master

