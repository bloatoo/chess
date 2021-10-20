# chess

Chess (name subject to change) is a TUI program for playing chess, either locally (soon), or via the Lichess API.

### Installation
Build from source:
```
git clone https://github.com/landchad/chess
cd chess
cargo install --path .
```

### Configuration
A default configuration file has been provided in the GitHub repository. Move/copy that file to `~/.config/chess.toml` and configure it to your liking.

As of now, a Lichess API key must be provided for any functionality. Offline games will be added later.

### Default Keybinds

```
q | Quit
hjkl + arrow keys | Move the cursor during games
enter | Select a menu item or a piece, or move the selected piece

```
## Preview

![Preview](media/preview.png?raw=true "Preview")
