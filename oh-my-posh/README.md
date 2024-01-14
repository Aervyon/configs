# oh-my-posh

These setups are for an oh-my-posh config (basically ohmyzsh but for more shells)
May or may not be a drop in replacement. You may need to edit some things.

## Configs preference (in order)

1. night-owl (requires a Nerd Font)
2. stelbent.minimal
3. JanDeDobbeleer (requires a Nerd Font)
4. probua.minimal

## To use with PowerShell Core:

(have oh-my-posh installed first)

Windows: $HOME/Documents/Powershell/Microsoft.PowerShell_profile.ps1

*for the script below replace `$HOME` with your actual home variable, and `theme` with your theme  of choice
```pwsh
/path/to/oh-my-posh init pwsh -c '$HOME/OMP/{theme}.omp.json' | Invoke-Expression
```
