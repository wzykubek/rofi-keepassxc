# rofi-keepassxc

## Description
Simple keepassxc-cli frontent in rofi menu.

## Installation
### Dependencies
Package | Description
:--- | :---
rofi | application menu, dmenu replacement
keepassxc | open-source password manager

### Install dependencies
#### Arch Linux
```
sudo pacman -S --needed rofi keepassxc zsh
```
#### Debian/Ubuntu
```
sudo apt install rofi keepassxc zsh
```
#### Fedora
```
sudo dnf install rofi keepassxc zsh
```
#### openSUSE
```
sudo zypper in rofi keepassxc zsh
```
### Clone repository
```
git clone https://github.com/samedamci/rofi-keepassxc
```
### Usage
* Bind this script (e.g. in sxhkd or i3wm config) to any key or start it `./rofi-keepassxc/rofi-keepassxc`.
* Enter your keepassxc database unlocking password.
* Select any entry and click enter to clip password for this entry.
