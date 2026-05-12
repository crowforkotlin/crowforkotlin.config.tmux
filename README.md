# crowforkotlin.config.tmux

Unix-like tmux configuration branch.

## Clone

```bash
mkdir -p ~/.config
git clone --recurse-submodules -b unix-like https://github.com/crowforkotlin/crowforkotlin.config.tmux.git ~/.config/tmux
cd ~/.config/tmux
```

## Update

```bash
cd ~/.config/tmux
git pull origin unix-like
git submodule update --init --recursive
```

## Branch

- active branch: `unix-like`
- target platforms: Linux, macOS, and similar systems

## Included dependencies

- `plugins/catppuccin/tmux`
- `plugins/oh-my-tmux`
