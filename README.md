# tmux-powerux

Minimal tmux configuration for a modern, PowerShell-like experience with mouse support and a Ctrl+T popup menu.

## Features

- Mouse scrolling & pane selection  
- Right-click paste  
- Drag-to-copy behavior  
- Large scrollback history  
- Clipboard integration  
- Ctrl+T popup menu for quick actions  
- Lightweight & minimal  

## Ctrl+T Menu

Press **Ctrl + T** inside tmux to open:

- New window  
- Split horizontal / vertical  
- Session switcher  
- Kill pane  
- Copy mode  
- htop system monitor  
- Reload config  

## Installation

### One-line install

```bash
curl -fsSL https://raw.githubusercontent.com/<USER>/<REPO>/<BRANCH>/.tmux.conf -o ~/.tmux.conf \
&& sudo apt update \
&& sudo apt install -y tmux htop xclip \
&& (tmux info >/dev/null 2>&1 && tmux source-file ~/.tmux.conf || true)
```

Start tmux
`tmux new -s lab

Usage

Detach session
Ctrl + B → D

Reattach
`tmux attach -t lab

Open menu
Ctrl + T

Requirements

tmux ≥ 3.2 recommended

Works best with Windows Terminal, iTerm2, VS Code terminal, or Kitty
