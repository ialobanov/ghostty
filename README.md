# ghostty

```shell
mkdir $HOME/.config/ghostty
```

```shell
vim $HOME/.config/ghostty/config
```

```ini
term = xterm-256color # Terminal type for compatibility with most CLI apps
theme = duckbones
scrollback-limit = 100000 # Number of lines stored in scrollback history

background-opacity = 0.9
background-blur-radius = 20

font-family = "JetBrainsMono Nerd Font Mono"
font-size = 24

window-padding-x = 20 # Horizontal padding inside the terminal window


shell-integration-features = no-cursor
cursor-style = block              # Cursor shape
cursor-color = "#FFC300"          # Hex color for the cursor
cursor-style-blink = true         # Makes the cursor blink

window-inherit-working-directory = false  # Always start new windows in the specified directory
working-directory = "/Users/ivan"
```
