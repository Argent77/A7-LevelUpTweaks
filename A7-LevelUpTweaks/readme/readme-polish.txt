"Level Up" Icon Tweaks
~~~~~~~~~~~~~~~~~~~~~~

Author:     Argent77
Version:    2.4

Download:   https://github.com/Argent77/A7-LevelUpTweaks/releases/latest
Discussion: https://forums.beamdog.com/discussion/64259/mod-level-up-icon-tweaks


Opis
~~~~

Ta modyfikacja pozwoli ci ulepszyć ikonę zmiany poziomu w PST:EE.


Instalacja
~~~~~~~~~~

Jest to modyfikacja WeiDU, co oznacza, iż jest bardzo prosta w instalacji. Wystarczy rozpakować pobrane archiwum do katalogu z grą, a następnie uruchomić plik "setup-A7-LevelUpTweaks.exe".


Komponenty
~~~~~~~~~~

1. Umożliwia włączenie ikony zmiany poziomu w pliku baldur.lua

Ten komponent dodaje do gry możliwość włączania i wyłączania, z poziomu pliku baldur.lua, ikony zmiany poziomu.

Aby ręcznie włączyć pojawianie się ikony zmiany poziomu, otwórz plik baldur.lua i dopisz w nim linię:
  SetPrivateProfileString('Game Options','Show Level Up Icon','1')
  
Aby ręcznie wyłączyć pojawianie się ikony zmiany poziomu, otwórz plik baldur.lua i dopisz w nim linię:
  SetPrivateProfileString('Game Options','Show Level Up Icon','0')

Plik baldur.lua można znaleźć w "Dokumenty/Planescape Torment - Enhanced Edition".

Uwaga! Ta opcja nie zostanie automatycznie usunięta z pliku baldur.lua po odinstalowaniu modyfikacji.


2. Przenosi ikonę zmiany poziomu na portret postaci (wymaga pierwszego komponentu)

Ten komponent przenosi ikonę zmiany poziomu z paska zdrowia postaci w prawy górny róg jej portretu.



Credits
~~~~~~~

Coding and testing: Argent77

Italian translation: Aedan

Polish translation: memory (Stars of Mystra)


Copyright Notice
~~~~~~~~~~~~~~~~

The mod '"Level Up" Icon Tweak' is licensed under the "Creative Commons Attribution-ShareAlike 4.0 
International License" (http://creativecommons.org/licenses/by-sa/4.0/).


History
~~~~~~~

2.6
- Added Polish readme (thanks memory)

2.5
- Added Polish translation (thanks memory)

2.4
- Added Italian translation (thanks Aedan)

2.3
- Traified setup messages
- Added modder prefix to mod file and folder names
