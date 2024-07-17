# dotfiles



## Getting started
This repo contains config files for different tools. The dotfiles are provisioned into the correct folder by [GNU Stow](https://www.gnu.org/software/stow/)

## Setup dotfiles
```
cd ~
git clone https://gitlab.devops.telekom.de/christian.priess/dotfiles.git
```
Navigate into dotfile folder:
```
cd dotfiles
```
Install stow:
```
sudo apt-get install stow
``` 

Use stow to create symlinks from home directory to dotfiles folder:
```
stow .
``` 