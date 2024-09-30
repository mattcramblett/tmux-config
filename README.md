# tmux

Starting point came from: https://youtu.be/DzNmUNvnB04

[Tmux Cheatsheet](https://tmuxcheatsheet.com/)

## Install

```
git clone https://github.com/mattcramblett/tmux-config.git ~/.config/tmux
```

## Requirements

```
# install tmux
brew install tmux

# install package manager
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## Getting Started

Run with `tmux` and if the bottom bar is the default lime green, run:
`<prefix>:source-file ~/.conf/tmux/tmux`
And `<prefix>I` to install plugins.

## Custom Mappings

Prefix: `ctrl+space`

Window navigation (no prefix): `Shift-Left` and `Shift-Right`

Pane navigation (prefix): `h|j|k|l` (vim-keys)
