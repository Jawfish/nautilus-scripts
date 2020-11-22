# About
Adds scripts to the right-click menu of Nautilus, the default file explorer in most Gnome-based distributions.

# Installation
Place scripts in `~/.local/share/nautilus/scripts`, creating the directory if it does not exist.Run `chmod +x ~/.local/share/nautilus/scripts/*` if the scripts do not show up in the menu.

To add an icon to the script, right click it and select `Properties`, then click on the icon to select a new one. A variety icons can be found at `/usr/share/pixmaps/`, or you can use your own.

# Scripts
## Copy Path
Copies the path of the selected file.
### Requirements
#### xclip
##### Ubuntu: `sudo apt install xclip`
##### Arch: `pacman -Sy xclip`


## Open in Code
Opens the selected file in Visual Studio Code.
### Requirements
#### Visual Studio Code
##### Ubuntu: `sudo apt install code`
##### Arch: `pacman -Sy code`

## Shred
*By using this script, you assume all responsibility for any lost data.*

Recursively shreds the selected directory or file. Requires confirmation.


### Requirements
#### Zenity, Python 3.5 or newer
##### Ubuntu: `sudo apt install zenity python3`
##### Arch: `pacman -Sy zenity python`
