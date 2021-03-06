Terminal config for Mac OS X
============================

Requirements
------------

* Homebrew installed

Installation
------------

Brew packages:

* bash
* git
* bash-completion
* z
* direnv
* vim

Other:

* RVM

Clone the directory as `~/.config`

Bash
----

In `~/.bashrc` for the user and possibly root:

```bash
CONFIG_PATH=/FULL/PATH/TO/THE/HOME/DIRECTORY/.config/bash
. $CONFIG_PATH/rc
```

Vim
---

```bash
ln -s ~/.config/vim/rc .vimrc
```

Git
---

In `~/.gitconfig`

```
[user]
    name = FULL NAME
    email = EMAIL

[include]
    path = ~/.config/git/config
```

RVM
---

```bash
ln -s ~/.config/rvm/rc .rvmrc
```
