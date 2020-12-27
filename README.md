# Blacksmithery

This is my Mac OS setup with Ansible

Edit `config_vars.yml` file accordingly.

```ssh
make install
```

Resetting this repository's origin to be able to push

```bash
git remote set-url origin git@github.com:tentacode/blacksmithery.git
```

## Bonus

On a fresh install, remove all the Dock items in one command :

```bash
defaults delete com.apple.dock persistent-apps; killall Dock
```

## Mac specific

### AppStore

* Code Runner
* Pixelmator

### direct download

* Logitech Options

### Todo

* Node 12.14
* vagrant
* auto set origin of repository to ssh
* mysql set password root : https://stackoverflow.com/questions/57803604/homebrew-mariadb-mysql-installation-root-access-denied
* dark menu / dock : defaults write -g NSRequiresAquaSystemAppearance -bool Yes (https://apple.stackexchange.com/questions/337478/how-to-get-dark-menu-bar-and-dock-in-mojave-light-mode)
* add rocket

### Manual stuff

* Ctrl + Shift + 5 to open screenshot utility and change screenshot default folder.
