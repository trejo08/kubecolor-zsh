# Overview

`Kubecolor` is an opersource tool that prints colorized outputs from the main kubernetes cli tool `kubectl`, so this is a functional plugin thats allows you to add functional keyboard shortcuts to `ZSH` and `Oh-My-ZSH`
# Install

### 1 - Pre-Requisites
```bash
brew install hidetatz/tap/kubecolor
```
### 2 - Configure Kubecolor

Follow steps described in the official [GitHub Repo](https://github.com/hidetatz/kubecolor)

### 3 - Install this custom plugin

```bash
git clone git@github.com:trejo08/kubecolor-zsh.git $ZSH_CUSTOM/plugins/kubecolor-zsh
```

### 4 - Add to ZSHRC

Edit your `.zshrc` config file  and add into the plugins configuration to enable shortcuts:

```bash
plugins=(
  git
  plugin-a
  plugin-b
  plugin-c
  kubecolor-zsh
  plugin-n
)
```

### 5 - Reload your shell
```bash
exec $SHELL
```

Enjoy it and don't forget submit any comment or issue.