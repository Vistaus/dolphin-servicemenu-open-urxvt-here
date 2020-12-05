# dolphin-servicemenu-openurxvthere
Adds an entry to open urxvt in the current path to Dolphin's File Manager contextual menu.

## Installation
Place `openUrxvtHere.desktop` in the KDE5 services folder, generally `~/.local/share/kservices5/ServiceMenus/` (for user service menus) or `/usr/share/kservices5/ServiceMenus/` (for system service menus). You can check the services path by running `kf5-config --path services`.

## Entry name
By default, the menu entry will read "Open Terminal Here". You can change this by editing the `Name` variable.
