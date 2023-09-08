"Stufe erhoehen"-Symbol einrichten
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Autor:      Argent77
Version:    2.7

Download:   https://github.com/Argent77/A7-LevelUpTweaks/releases/latest
            http://www.shsforums.net/files/file/1222-level-up-icon-tweaks/
Diskussion: https://forums.beamdog.com/discussion/64259/mod-level-up-icon-tweaks
            http://www.shsforums.net/topic/60061-level-up-icon-tweaks-pstee/


Übersicht
~~~~~~~~~

Diese Mod ermöglicht es, die Eigenschaften der "Erfahrungsstufe erhoehen"-Symbole in PST:EE zu verändern.


Installation
~~~~~~~~~~~~

Dies ist eine WeiDU Mod. Das bedeutet, sie ist sehr einfach zu installieren. Entpackt die heruntergeladene
Zipdatei in das Spieleverzeichnis und startet entweder „setup-A7-LevelUpTweaks.exe” (Windows) oder
„setup-A7-LevelUpTweaks.command” (macOS). Folgt den Anweisungen des Programms und die Mod ist startbereit.


Modkomponenten
~~~~~~~~~~~~~~

1. Aktivierungsschlüssel für "Stufe erhöhen"-Symbol in baldur.lua einrichten

Diese Komponente richtet eine Option ein, mit der man Benachrichtigungen zum Aufsteigen einer Erfahrungsstufe
mittels eines baldur.lua-Eintrags ein- oder ausschalten kann.

Um Benachrichtigungen zu aktivieren, öffnet die baldur.lua-Datei im Dokumentenordner des Spiels und fügt die
folgende Zeile hinzu:
  SetPrivateProfileString('Game Options','Show Level Up Icon','1')

Um Benachrichtigungen zu deaktivieren, öffnet die baldur.lua-Datei im Dokumentenordner des Spiels und setzt
die folgende Option:
  SetPrivateProfileString('Game Options','Show Level Up Icon','0')

Die baldur.lua befindet sich im Ordner "Meine Dokumente/Planescape Torment - Enhanced Edition".

Wichtig: Die Option wird nicht automatisch aus der baldur.lua entfernt, wenn die Mod deinstalliert wird.


2. "Stufe erhöhen"-Symbol in Charakterporträts verschieben (benötigt die Hauptkomponente)

Diese Komponente verschiebt das "Stufe erhöhen"-Symbol vom Gesundheitsbalken direkt in die obere rechte Ecke
der Charakterporträts.


Credits
~~~~~~~

Coding and testing: Argent77

French translation: Jazira

Italian translation: Aedan

Polish translation: memory (Stars of Mystra)


Copyright Notice
~~~~~~~~~~~~~~~~

The mod '"Level Up" Icon Tweak' is licensed under the "Creative Commons Attribution-ShareAlike 4.0 
International License" (http://creativecommons.org/licenses/by-sa/4.0/).


History
~~~~~~~

2.7
- Added French translation (thanks Jazira)
- Added Project Infinity support

2.6
- Added German readme and translation
- Updated links in readme

2.5
- Added Polish readme and translation (thanks memory)

2.4
- Added Italian translation (thanks Aedan)

2.3
- Traified setup messages
- Added modder prefix to mod file and folder names
