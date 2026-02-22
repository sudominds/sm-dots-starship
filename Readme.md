# sm-dots-starship

### Starship cross-shell prompt:
https://starship.rs/guide/

### Theme
catppuccin starship theme:
https://github.com/catppuccin/starship/tree/main

### Starship config
Use this `starship.toml` by pointing `STARSHIP_CONFIG` at it and initializing Starship in your shell profile.

## Bash

Add to `~/.bashrc`:

```bash
export STARSHIP_CONFIG="/path/to/starship.toml"
eval "$(starship init bash)"
```

## Zsh

Add to `~/.zshrc`:

```zsh
export STARSHIP_CONFIG="/path/to/starship.toml"
eval "$(starship init zsh)"
```

## PowerShell

Add to `$PROFILE`:
open profile 
```powershell
notepad $profile
```

```powershell
$env:STARSHIP_CONFIG = "C:\\path\\to\\starship.toml"
Invoke-Expression (&starship init powershell)
```


