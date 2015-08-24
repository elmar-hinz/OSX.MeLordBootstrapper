# OSX.MeLordBootstrapper

Bootstrap a freshly created user with Hombrew, 
Ansible, Me and Lord or your existing user. 

## Usage

```
ruby bootstrapper.rb
````

## Installs

* [Homebrew](http://brew.sh)
* [Ansible](https://en.wikipedia.org/wiki/Ansible_(software))
* [Me (optional)](https://github.com/elmar-hinz/OSX.Me)
* [Lord (optional)](https://github.com/elmar-hinz/OSX.Lord)

The installation and maintainance of further software is managed by [**Me**](https://github.com/elmar-hinz/OSX.Me) based on Ansible Yaml files.

## Features

* Installation of Hombrew with a prefix
* Installation into the home directory
* Installation on USB-Stick
* Fully interactive 
* Full Rollback in case of exeption or deliberate interrupt

## TODO

* stepping over to Me setup
* replace fully qualified user dir with $HOME in .bashrc
