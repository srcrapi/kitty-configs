# kitty-configs
My personal simple kitty configuration.

<!--Component-->
- **Terminal:** [kitty](https://github.com/kovidgoyal/kitty)

<!--Instalation-->
## Instalation of kitty.
#### Arch Linux
```bash
# Arch Linux
$ yay -S kitty

# Install git if you don't have it
$ sudo pacman -S git

# If you want the dracula theme install the zip file below and follow the steps
$ unzip kitty-master.zip
$ cd kitty-master
$ cp dracula.conf diff.conf ~/.config/kitty/
$ echo "include dracula.conf" >> ~/.config/kitty/kitty.conf
  
$ git clone https://github.com/srcrapi/kitty-configs.git
$ cd kitty-configs
$ cp kitty/kitty.conf ~/.config/kitty
```
#### Ubuntu
```bash
# Ubuntu
$ sudo apt install kitty

# Install git if you don't have it
$ sudo apt install git

# If you want the dracula theme install the zip file below and follow the steps
$ unzip kitty-master.zip
$ cd kitty-master
$ cp dracula.conf diff.conf ~/.config/kitty/
$ echo "include dracula.conf" >> ~/.config/kitty/kitty.conf
  
$ git clone https://github.com/srcrapi/kitty-configs.git
$ cd kitty-configs
$ cp kitty/kitty.conf ~/.config/kitty
```
