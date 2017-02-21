# Yproximite OSX Installer

Easily configure your osx installation with our standard stack

- Virtualbox
- Vagrant (with hostmanager plugin)
- Zsh & Oh-My-Zsh
- Git

## Requirements

In order to run this script you need to install:
 - the osx command line tools (`make`), 
 - [homebrew](http://brew.sh/index_fr.html)
 - homebrew cask (`brew install cask`)
 - wget (`brew install wget`)
 - ansible (`brew install ansible`)

## Installation

```
wget -O installer.zip https://github.com/Yproximite/osx-installer/archive/master.zip
unzip installer
cd installer
ansible-playbook -i hosts -K playbook.yml
```
