# Yproximite OSX Installer

Easily configure your osx installation with our standard stack

- Virtualbox
- Vagrant (with hostmanager plugin)
- Zsh & Oh-My-Zsh
- Git

## Requirements

In order to run this script you need to install:
 - the osx command line tools, 
 - homebrew
 - homebrew cask
 - ansible

## Installation

```
wget -O installer.zip https://github.com/Yproximite/osx-installer/archive/master.zip
unzip installer
cd installer
ansible-playbook -i hosts -K playbook.yml
```
