# rofi-keepassxc
![GitHub release](https://img.shields.io/github/v/release/samedamci/rofi-keepassxc?logo=github&style=for-the-badge)
## Description
Simple keepassxc-cli frontent in rofi menu.

### Features
Function | keepassxc-cli | rofi-keepassxc
:--- | :--- | :---
Use more than one DBs | yes | no (in future yes)
Add new entry to DB | yes | no (in future yes)
Groups support | yes | no (in future yes)
Analyze passwords for weaknesses and problems | yes | no
Copy password to clipboard | yes | **yes**
Copy username to clipboard | **no**| **yes**
Copy URL to clipboard | **no** | **yes**
Edit entry | yes | **yes**
Estimate the entropy of a password | yes | no
Generate random password | yes | **yes**
List database entries | yes | **yes**
Remove entries from DB | yes | **yes**
Show entry informations | yes | **yes**

## Installation
### Dependencies
Package | Description
:--- | :---
rofi | application menu, dmenu replacement
keepassxc | open-source password manager
zsh | alternative shell and interpreter
xclip | CLI to the X11 clipboard

### Install dependencies
#### Arch Linux
```
sudo pacman -S --needed rofi keepassxc zsh xclip
```
#### Debian/Ubuntu
```
sudo apt install rofi keepassxc zsh xclip
```
#### Fedora
```
sudo dnf install rofi keepassxc zsh xclip
```
#### openSUSE
```
sudo zypper in rofi keepassxc zsh xclip
```
### Clone repository
```
git clone https://github.com/samedamci/rofi-keepassxc
```
### Usage
* Bind this script (e.g. in sxhkd or i3wm config) to any key or start it `./rofi-keepassxc/rofi-keepassxc`.
* Use `-d` or `--database` argument and specify your keepass database path.
* Enter your keepass database master password.
* Select any entry and use option which you want.
