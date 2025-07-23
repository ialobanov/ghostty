# ghostty

## Theme

```shell
sudo vim /Applications/Ghostty.app/Contents/Resources/ghostty/themes/Whimsy-edited
```

```properties
palette = 0=#adadd9
palette = 1=#ef6487
palette = 2=#5eca89
palette = 3=#FFC300
palette = 4=#65aef7
palette = 5=#aa7ff0
palette = 6=#43c1be
palette = 7=#ffffff
palette = 8=#adadd9
palette = 9=#ef6487
palette = 10=#5eca89
palette = 11=#FFC300
palette = 12=#65aef7
palette = 13=#aa7ff0
palette = 14=#43c1be
palette = 15=#ffffff
background = #29283b
foreground = #e6e6f7
cursor-color = #b3b0d6
cursor-text = #535178
selection-background = #3d3c58
selection-foreground = #ffffff
```

## Configuration

```shell
mkdir -p $HOME/.config/ghostty && vim $HOME/.config/ghostty/config
```

```properties
term = xterm-256color
theme = Whimsy-edited``

background-opacity = 1
background-blur-radius = 20

font-family = "JetBrainsMono Nerd Font Mono"
font-size = 22

window-padding-x = 20
window-vsync = true


shell-integration-features = no-cursor
cursor-style = block
cursor-color = "#FFC300"
cursor-style-blink = true

window-inherit-working-directory = false
working-directory = "home"

macos-titlebar-style = tabs
```
