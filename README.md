scoop / neovim / oh-my-posh / PSReadLine / Fzf / Icons

```
# Prompt
Import-Module posh-git
Import-Module oh-my-posh
Import-Module Terminal-Icons
Set-PoshPrompt Material

# PSReadLine
Set-PSReadLineKeyHandler -Chord 'Ctrl-d' -Function DeleteChar
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView

# Icons
Import-Module -Name Terminal-Icons

# Fzf
Import-Module PSFzf
# Set-PsFzfOption -PSReadlineChordProvider 'Ctrl+f' -PSReadlineChordReverseHistory 'Ctrl+r'

# Alias
Set-Alias vim nvim
Set-Alias ll ls
Set-Alias g git
Set-Alias grep findstr
Set-Alias tig 'C:\Program Files\Git\usr\bin\tig.exe'
Set-Alias less 'C:\Program Files\Git\usr\bin\less.exe'
```
