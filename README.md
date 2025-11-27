# AeroSpace Config

My personal configuration for [AeroSpace](https://github.com/nikitabobko/AeroSpace) - a tiling window manager for macOS.

## Installation

1. Install AeroSpace (using Homebrew):

   ```bash
   brew install --cask nikitabobko/tap/aerospace
   ```

2. Copy the configuration file to your home directory:

   ```bash
   cp .aerospace.toml ~/.aerospace.toml
   ```

3. Reload the configuration:
   - Restart AeroSpace
   - Or run: `aerospace reload-config`

## Key Bindings

| Key | Action |
|-----|--------|
| `Alt + J/K/I/L` | Focus left/down/up/right |
| `Alt + Cmd + J/K/I/L` | Move window left/down/up/right |
| `Alt + 1-9` | Switch to workspace 1-9 |
| `Alt + Cmd + 1-9` | Move window to workspace 1-9 |
| `Alt + F` | Toggle floating/tiling |
| `Alt + Tab` | Switch to previous workspace |

