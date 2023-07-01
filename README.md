# win-dots
dotfiles for Windows

```pwsh
New-Item -ItemType SymbolicLink -Path "" -Target ""
New-Item -ItemType SymbolicLink -Path "C:\Users\charles\.leptonrc" -Target "D:\Workspace\win-dots\home\.leptonrc"
New-Item -ItemType SymbolicLink -Path "C:\Users\charles\.gitconfig" -Target "D:\Workspace\win-dots\home\.gitconfig"
New-Item -ItemType SymbolicLink -Path "C:\Users\charles\Documents\PowerShell\Microsoft.PowerShell_profile.ps1" -Target "D:\Workspace\win-dots\home\Documents\PowerShell\Microsoft.PowerShell_profile.ps1"
New-Item -ItemType SymbolicLink -Path "C:\Users\charles\Documents\PowerShell\powershell.config.json" -Target "D:\Workspace\win-dots\home\Documents\PowerShell\powershell.config.json"
New-Item -ItemType SymbolicLink -Path "C:\Users\charles/AppData/Local/Packages/Microsoft.WindowsTerminal_8wekyb3d8bbwe/LocalState/settings.json" -Target "D:\Workspace\win-dots\home\AppData/Local/Packages/Microsoft.WindowsTerminal_8wekyb3d8bbwe/LocalState/settings.json"
New-Item -ItemType SymbolicLink -Path "C:\Users\charles\.logseq" -Target "D:\Workspace\win-dots\home\.logseq"
New-Item -ItemType SymbolicLink -Path "C:\Users\charles\.config\starship.toml" -Target "D:\Workspace\dotfiles\Starship\.config\starship.toml"
mkdir C:\Users\charles\AppData\Roaming\lazygit
New-Item -ItemType SymbolicLink -Path "C:\Users\charles\AppData\Roaming\lazygit\config.yml" -Target "D:\Workspace\dotfiles\Lazygit\.config\lazygit\config.yml"
```
