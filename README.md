# rofi-keepassxc
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/samedamci/rofi-keepassxc?label=ver&logo=github&style=for-the-badge)
## Description
Simple keepassxc-cli frontend in rofi menu.

### Features
Function | keepassxc-cli | rofi-keepassxc
:--- | :--- | :---
Use more than one DBs | yes | no
Add new entry to DB | yes | **yes**
Groups support | yes | no
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

### Installation guide
## Arch Linux
Install package from [AUR](https://aur.archlinux.org/packages/rofi-keepassxc/).
```shell
yay -S rofi-keepassxc
```
Or version from git master branch `rofi-keepassxc-git`.
## From source
Clone this repo.
```shell
git clone https://github.com/samedamci/rofi-keepassxc
cd rofi-keepassxc
```
Add script to your PATH or use relative path to run `./rofi-keepassxc`.
