# My Configurations (dotfiles)

## Requirements

### Git

```
xcode-select –-install
```

### Brew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### GNU Stow

```
brew install stow
```

## Installation

First, checkout the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/danielluna90/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
