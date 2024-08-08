# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

#### Linux

```
sudo apt-get install git
```

#### Mac OS

```
brew install git
```

### Stow

#### Linux

```
sudo apt-get update -y
sudo apt-get install -y stow
```

#### Mac OS

```
brew install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/leonardoXoliveira/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
