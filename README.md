# Linux

colors

```bash
for i in {0..255}; do print -Pn "%K{$i}  %k%F{$i}${(l:3::0:)i}%f " ${${(M)$((i%6)):#3}:+$'\n'}; done
```

## Windows

Install oh-my-posh

```ps1
Install-Module oh-my-posh -Scope CurrentUser -AllowPrerelease
```

```ps1
Get-PoshThemes
```

Set font name CaskaydiaCove NF in Windows Terminal font settings.
