# crowforkotlin.config.tmux

Tmux configuration repository split by branch.

## Branches

- `main`: entry branch with clone instructions
- `unix-like`: Linux, macOS, and similar environments
- `windows`: Windows-oriented setup

## Clone `unix-like`

```bash
mkdir -p ~/.config
git clone -b unix-like https://github.com/crowforkotlin/crowforkotlin.config.tmux.git ~/.config/tmux
cd ~/.config/tmux
```

## Clone `windows`

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\\.config" | Out-Null
git clone -b windows https://github.com/crowforkotlin/crowforkotlin.config.tmux.git "$env:USERPROFILE\\.config\\tmux"
Set-Location "$env:USERPROFILE\\.config\\tmux"
```

## Switch later

```bash
git fetch origin
git switch unix-like
git switch windows
```
