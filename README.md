# cheat-cheet-cheet

An diesem Cheet mitarbeiten:

`git clone git@github.com:HorstFrank/cheat-cheet-cheet.git`

um gleich zu starten:

`git clone git@github.com:HorstFrank/cheat-cheet-cheet.git && cd cheat-cheet-cheet && git checkout -b dev && code README.md`

Um deine änderungen beizutragen:

- `git add . && git commit -m "Add new Things" && git push --set-upstream origin dev`

Markdownsachen:

[Das Markdown-Cheat-Cheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

## GitHub

Grundsätzlich gilt in der Shell das Schema `[Kommando][leerzeichen][Parameter]`

- `git clone SSHKEY` Erstmalig alles unterladen
- `cd ORDNERNAME` in den Ordner wechseln
- `git checkout -b BRANCH` in den Branch gehen
- `git add .` alle neuen Files & Ordner Stagen
- `git status` checken ob alles richtig ist
- `git commit -m "Add Zusammenfassung"` Push vorbrereiten
- `git push -u origin BRANCH` <--- Erstmalig | Danach ---> `git push` Hochladen

Bei späteren arbeiten an einem Repository

- `git pull` neuesten stand holen
- `git checkout -b BRANCH` in den Branch gehen
- `git add .` alle neuen Files & Ordner Stagen
- `git status` checken ob alles richtig ist
- `git commit -m "Add Zusammenfassung"` Push vorbrereiten
- `git push` Hochladen

### Links

- [Das Git-Cheat-Cheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)
- [Git-Spiel](https://learngitbranching.js.org/)

## Welche Programme, Plugins usw. brauchen wir?

- VSCode
  - Prettier Code formatter
  - styleint
  - HTMLHint
- Node.js
- [oh My zShell](https://ohmyz.sh/#install)

### Links

- [VSCode Shortcuts](https://code.visualstudio.com/docs/getstarted/keybindings#_keyboard-shortcuts-reference)

## Shell Kommandos

- `ls`- Zeigt den Inhalt des Verzeichnisses an, in dem man sich gerade befindet
- `ls -l` wie `ls` aber mehr Informationen zu den Dateiberechtigungen.
- `ls -a` zeigt auch `versteckte` Files an
- `ls -al` eine Kombination aus `ls -l` und `ls -a`
- `cd ..` wechselt eine Verzeichnisebene höher
- `cd FOLDERNAME/` wechselt in das mit `FOLDERNAME` angegebene Verzeichnis.
- `mkdir VERZEICHNISNAME` erstellt ein Verzeichnis mit dem bei `VERZEICHNISNAMEN` angegebene Verzeichnisnamen. (Dummer Satz, stimmt aber)
- `touch DATEINAME.SUFFIX` erstellt eine (leere) Datei mit DATEINAMEN und der angegebenen SUFFIX
- `code .` öffnet VSCode. Wenn nicht, siehe `VSCode` im Abschnitt Installation
- `code DATEINAME` öffnet in VSCode die angegebene Datei
- `code VERZEICHNISNAME/` öffnet in VSCode das angegebene Verzeichnis. Dort werden alle Unterverzeichnisse und Datein angezeigt.
- `rm -r DATEINAME` Löscht eine Datei (oder leeres Verzeichnis) ohne Rückfrage oder Papierkorb oder sowas.
- `rm -rf VERZEICHNISNAME/` löscht ein Verzeichnis und die darin enthaltenen Datein und Unterverzeichnisse. Benutz das nur, wenn du dir wirklcih sicher bist, was du da löschen willst. Wenn du damit dein System schrottest, haste danach viel Arbeit vor dir.

### Links

- [Shell-Kommando Cheat-Cheet](https://www.git-tower.com/blog/media/pages/posts/command-line-cheat-sheet/1073300074-1610436652/command-line-cheat-sheet-large01.png)

# Unsortierte Textschnippsel

Hier einfach alles erstmal rein ...
