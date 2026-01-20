# 1 - Test sind rot

Die Zeile mit com.example muss aus beiden Dateien gelöscht werden,
die Division durch 0 muss in Calculator.java geändert werden (b).

# 2 - schlechte Commit Message

Update -> Es ist unklar was geupdatet wurde -> Besserer Commit: Updated Main Class
Fix Bug -> Es ist unklar welcher Bug gefixt wurde -> Besserer Commit: Fix Bug regarding Movement
stuff -> Unersichtlich was überhaupt gemacht wurde -> Besserer Commit: Added files, changed class xy, etc.
Adjust logic -> Welche Logic wurde angepasst, bzw. von welchem Code -> Besserer Commit: Adjusted logic in method xy
Temporary fix -> Es sollte genau beschrieben werden was gefixt wurde, auch wenn es nur temporär ist -> Temporary fix for hitbox bug

# 3 - Repository aufräumen

debug.log -> Kein sinnvoller Inhalt

# 4 - Datei wiederherstellen

Ich habe mit git status nachgesehen, wo Files gelöscht wurden. Zu dem Commit habe ich die
ID kopiert und git revert ID ausgeführt.

# Panic Room - Finale Zusammenfassung


## Team
- ### CMMJ
- Clemens
- Mark
- Matthias
- Julain

## Probleme und Lösungen im Panic Room
### Lösungsschritte - Problem 1
1. Division auf a/b ändern, da a/0 illegal ist, dass sollte auch den falschen test Fixen
2. Das Package Löschen
3. Neuen Test Complex_Math schreiben.

### Lösungsschritte - Problem 2
- Schlechte Commit Message: Stuff
- Begründung: Stuff ist nichts aussagend.
- Verbesserung: Debug-Commitet

### Lösungsschritte - Problem 3
- Debug.log
- Begründung: Die Datei wird einmal angelegt und es wird nur eine Zeile hinein Geschrieben.

### Lösungsschritte - Problem 4
1. Gelöschte Datei suchen: usage.md.
2. mit git checkout in die Version vor dem löschen wechseln.
3. Datei an einem anderem Ort Zwischenspeicher.
4. mit git checkout wieder zurück wechseln.
5. Datei hinen kopieren.

## Problemvermeidung
- Gute Commit Messages
- Gute Teamkommunikation
- Nachdenken
- Repo ordentlich halten
- Dateien in absprache Löschen

## Problemlösung
- Nachdenken
- Im Team miteinder denken
