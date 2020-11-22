# About
Adds scripts to the right-click menu of Nautilus, the default file explorer in most Gnome-based distributions.

## Why do some of the scripts use Python?
File operations are dangerous, and Bash is unwieldy. I am more confident in my ability to write safe Python than safe Bash.

# Installation
Place scripts in `~/.local/share/nautilus/scripts`, creating the directory if it does not exist. Run `chmod +x ~/.local/share/nautilus/scripts/*` if the scripts do not show up in the menu.

To add an icon to the script, right click it and select `Properties`, then click on the icon to select a new one. A variety icons can be found at `/usr/share/pixmaps/`, or you can use your own.

# Scripts
## Copy Path: 
Copies the path of the selected file.
### Requirements:
#### xclip
##### Ubuntu: `sudo apt install xclip`
##### Arch: `pacman -Sy xclip`


## Open in Code: 
Opens the selected file in Visual Studio Code.
### Requirements:
#### Visual Studio Code
##### Ubuntu: `sudo apt install code`
##### Arch: `pacman -Sy code`

## Shred:
*By using this script, you assume all responsibility for any data lost as a result of its use.*

Recursively shreds the selected directory or file. Requires confirmation.


### Requirements:
#### zenity
##### Ubuntu: `sudo apt install zenity`
##### Arch: `pacman -Sy zenity`