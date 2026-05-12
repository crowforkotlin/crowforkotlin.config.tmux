# crowforkotlin.config.tmux

Windows tmux configuration branch.

## Clone

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\\.config" | Out-Null
git clone -b windows https://github.com/crowforkotlin/crowforkotlin.config.tmux.git "$env:USERPROFILE\\.config\\tmux"
Set-Location "$env:USERPROFILE\\.config\\tmux"
```

## Update

```powershell
Set-Location "$env:USERPROFILE\\.config\\tmux"
git pull origin windows
```

## Branch

- active branch: `windows`
- target platform: Windows
