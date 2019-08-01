"Level Up" Icon Tweaks
~~~~~~~~~~~~~~~~~~~~~~

Author:     Argent77
Version:    2.5

Download:   https://github.com/Argent77/A7-LevelUpTweaks/releases/latest
            http://www.shsforums.net/files/file/1222-level-up-icon-tweaks/
Discussion: https://forums.beamdog.com/discussion/64259/mod-level-up-icon-tweaks
            http://www.shsforums.net/topic/60061-level-up-icon-tweaks-pstee/


Overview
~~~~~~~~

This mod allows you to tweak the "level up" notification icon in PST:EE.


Installation
~~~~~~~~~~~~

This is a WeiDU mod, that means it is very easy to install. Simply unpack the downloaded archive 
into your game directory and run "setup-A7-LevelUpTweaks.exe".


Mod Components
~~~~~~~~~~~~~~

1. Enable "level up" icon activation switch in baldur.lua

This component installs an option to turn level up icon notifications on or off and enables 
it in the baldur.lua.

To manually enable level up icon notifications, open baldur.lua and add the following option:
  SetPrivateProfileString('Game Options','Show Level Up Icon','1')

To manually disable level up icon notifications, open baldur.lua and set the following option:
  SetPrivateProfileString('Game Options','Show Level Up Icon','0')

The baldur.lua file can be found in "Documents/Planescape Torment - Enhanced Edition".

Important: The option will not be removed from baldur.lua when you uninstall the mod.


2. Move "level up" icon into character portrait (requires first component)

This component moves level up icons from the health bar up into the top right corner of 
the character portraits.


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
- Added German readme and translation
- Updated links in readme

2.5
- Added Polish readme and translation (thanks memory)

2.4
- Added Italian translation (thanks Aedan)

2.3
- Traified setup messages
- Added modder prefix to mod file and folder names
