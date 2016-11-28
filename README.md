# Dotfiles

my dotfiles from fedora 23

## About

https://pypi.python.org/pypi/dotfiles

## Install

**Install dotiles**

```bash
sudo pip install dotfiles
```

**Configuration file ~/.dotfilesrc**

```
[dotfiles]
repository = ~/Dotfiles
ignore = [
    '.git',
    '.gitignore',
    '*.swp']
```

**Clone**

```bash
git clone git@github.com:danielkraic/dotfiles.git Dotfiles
```

**Usage**

```bash
dotfiles -s # sync
dotfiles -l # list
dotfiles -a file # add file
dotfiles -c # check
```

