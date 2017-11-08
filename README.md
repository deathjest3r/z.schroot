# z.schroot
## Notification whether the shell was spawned in a chroot or not

## What it does:

This plugin shows you if you are executing in a chroot or not.

## How it works:

* It just checks the fs node of '/'.

## Installation:

* Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
* Then:
```
cd ~/.oh-my-zsh/plugins
git clone https://github.com/deathjest3r/z.schroot.git
```

* Add z.schroot.me to plugins entry to ```~./.zshrc```
```
plugins=(... z.schroot)
```
* Make sure your zsh theme does not overwrite the ```RPROMPT``` variable. In
  this case modify it to ```RPROMPT=${RPROMT} ...```
