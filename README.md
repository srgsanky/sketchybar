# srgsanky's sketchy bar configuration

<https://github.com/FelixKratz/SketchyBar>

### Installation

<https://felixkratz.github.io/SketchyBar/setup>

```bash
brew tap FelixKratz/formulae
brew install sketchybar
```

Clone configuration

```bash
mkdir -p ~/.config
git clone https://github.com/srgsanky/sketchybar ~/.config/sketchybar/
```

#### Install nerd font

```bash
# List all available fonts
brew search "/font-/"

# List installed fonts
brew list --cask | grep font

brew install --cask font-hack-nerd-font
brew install --cask font-jetbrains-mono-nerd-font

# View font name to use in configurations
brew info font-hack-nerd-font
```

Startup

```bash
brew services start sketchybar
```

### Reload config

To reload the config, use

```bash
sketchybar --reload
```

