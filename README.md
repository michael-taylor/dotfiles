## Requirements

- JetBrains Mono Font: https://www.jetbrains.com/lp/mono/
- JetBrains Mono Nerd Font: https://www.nerdfonts.com/font-downloads

## Included software configurations

- Oh My Posh
- PowerShell
- Sublime Merge
- Sublime Text

## Notes

### PowerShell

Your PowerShell PROFILE should contain the following line to enable Oh My Posh:

```
oh-my-posh init --config "~/AppData/Roaming/Oh My Posh/dracula.omp.json" pwsh | Invoke-Expression
```

Also, to make directory entries in Get-ChildItem output easier to read, the following line in 
PROFILE will make the foreground text darker:

```
$PSStyle.FileInfo.Directory = "`e[30;44m"
```

### Sublime Text

When first starting Sublime Text there will be some errors. Follow these instructions:

1. Install Package Control
2. Wait for packages to install
3. Restart Sublime Text
4. Wait for file icons to finish installing
5. You can restart Sublime Text again (may not be necessary).
