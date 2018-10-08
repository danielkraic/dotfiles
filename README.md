# Dotfiles

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
    'README.md',
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

### Before install

* save ssh keys
* pass - save passwords
* save gsh.config

### Post-install

* apt

```bash
sudo apt install \
    build-essential \
    clang \
    curl \
    git \
    jq \
    pass \
    mc \
    python3-dev \
    sl \
    tree \
    zsh
```

* pip

```bash
sudo pip3 install \
    black \
    dotfiles \
    flake8 \
    httpie \
    ipython \
    pipenv \
    thefuck
```

* ohmyzsh

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

* dotfiles: https://github.com/danielkraic/dotfiles

* bat: https://github.com/sharkdp/bat

* atom: https://atom.io/

* golang: https://golang.org/doc/install

* gsh

```bash
go get -v github.com/danielkraic/gsh
```

* grc: https://github.com/garabik/grc

* fzf (instaled as part of vim plugins) - https://github.com/junegunn/fzf

* docker: https://docs.docker.com/install/linux/docker-ce/ubuntu/

* kubectl: https://kubernetes.io/docs/tasks/tools/install-kubectl/

* minikube: https://github.com/kubernetes/minikube/releases and https://github.com/kubernetes/minikube/blob/master/docs/drivers.md#kvm2-driver

* azure cli: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest

* grpc c++: https://github.com/grpc/grpc/blob/v1.15.0/BUILDING.md

* remmina

```bash
sudo add-apt-repository ppa:remmina-ppa-team/remmina-next
sudo apt update && sudo apt install remmina
```


