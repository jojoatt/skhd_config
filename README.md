# SKHD Setup
![Operating System](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=apple&logoColor=white)

## Installation
To install Skhd, run the following command:
```
brew install koekeishiya/formulae/skhd
```

## Setup
1. Clone config
```
git clone git@github.com:jojoatt/yabai_config.git ~/.config/skhd
```
The skhd config will be in `skhdrc` file at `~/.config/skhd` path

2. That's it !

## Usage
To start skhd:
```
skhd --start-service
```
To restart skhd:
```
skhd --restart-service
```
To stop skhd:
```
skhd --stop-service
```
To reload config file of skhd:
```
skhd --reload
```
or
```
skhd -r
```

