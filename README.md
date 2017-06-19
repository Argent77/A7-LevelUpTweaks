# "Level Up" Icon Tweaks
*A tweak mod for PST:EE that allows more control over the display of level up icons*

## Overview

This mod allows you to tweak the "level up" notification icon in PST:EE.

## Mod Components

### 1. Enable "level up" icon activation switch in baldur.lua

This component installs an option to turn level up icon notifications on or off and enables it in the baldur.lua.

To manually enable level up icon notifications, open baldur.lua and add the following option:
`SetPrivateProfileString('Game Options','Show Level Up Icon','1')`

To manually disable level up icon notifications, open baldur.lua and set the following option:
`SetPrivateProfileString('Game Options','Show Level Up Icon','0')`

The baldur.lua file can be found in `Documents/Planescape Torment - Enhanced Edition`.

**Important:** The option will not be removed from baldur.lua when you uninstall the mod.


### 2. Move "level up" icon into character portrait (requires first component)

This component moves level up icons from the health bar up into the top right corner of the character portraits.


## Copyright Notice

The mod *'"Level Up" Icon Tweak'* is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
