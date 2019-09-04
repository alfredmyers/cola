# Command line Cola

|bash |cmd |PowerShell|
|---|---|---|
||[mountvol](https://docs.microsoft.com/windows-server/administration/windows-commands/mountvol) S: /s|[Get-Partition](https://docs.microsoft.com/powershell/module/storage/get-partition) \| ? IsSystem \| [Set-Partition](https://docs.microsoft.com/powershell/module/storage/set-partition) -NewDriveLetter S|
||net start|[Start-Service](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Start-Service)
||net stop|[Stop-Service](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Stop-Service)
||[sc query](https://docs.microsoft.com/windows-server/administration/windows-commands/sc-query)|[Get-Service](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Get-Service)|
||sc start|[Start-Service](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Start-Service)
||sc stop|[Stop-Service](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Stop-Service)
|cat|[type](https://docs.microsoft.com/windows-server/administration/windows-commands/type)|[Get-Content](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Get-Content)|
|cd|[cd](https://docs.microsoft.com/windows-server/administration/windows-commands/cd)|[Set-Location](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Set-Location)|
|cd|[chdir](https://docs.microsoft.com/windows-server/administration/windows-commands/chdir_1)|[Set-Location](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Set-Location)|
|cp|[copy](https://docs.microsoft.com/windows-server/administration/windows-commands/copy)|[Copy-Item](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/copy-item)|
|clear|[cls](https://docs.microsoft.com/windows-server/administration/windows-commands/cls)|[Clear-Host](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/functions/clear-host)|
|dir|[dir](https://docs.microsoft.com/windows-server/administration/windows-commands/dir)|[Get-ChildItem](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/get-childitem)|
|head||[Get-Content -TotalCount 10](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Get-Content)|
|history|[doskey /h](https://docs.microsoft.com/windows-server/administration/windows-commands/doskey)|[Get-History](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Core/Get-History)|
|hostname|[hostname](https://docs.microsoft.com/windows-server/administration/windows-commands/hostname)|$env:computername|
|kill|[taskkill](https://docs.microsoft.com/windows-server/administration/windows-commands/taskkill)|[Stop-Process](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Stop-Process)|
|mkdir|[md](https://docs.microsoft.com/windows-server/administration/windows-commands/md)|[New-Item -ItemType Directory](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/new-item)|
|mkdir|[mkdir](https://docs.microsoft.com/windows-server/administration/windows-commands/mkdir)|[New-Item -ItemType Directory](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/new-item)|
|mv|[move](https://docs.microsoft.com/windows-server/administration/windows-commands/move)|[Move-Item](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/move-item)|
|mv|[ren](https://docs.microsoft.com/windows-server/administration/windows-commands/ren)|[Rename-Item](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/rename-item)|
|open<sup>1</sup>|[start](https://docs.microsoft.com/windows-server/administration/windows-commands/start)|[Start-Process](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/start-process)|
|ping|[ping](https://docs.microsoft.com/windows-server/administration/windows-commands/ping)|[Test-Connection](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/test-connection)|
|ps|[tasklist](https://docs.microsoft.com/windows-server/administration/windows-commands/tasklist)|[Get-Process](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Get-Process)|
|pwd|[cd](https://docs.microsoft.com/windows-server/administration/windows-commands/cd)|[Get-Location](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/get-location)|
|rm|[del](https://docs.microsoft.com/windows-server/administration/windows-commands/del)|[Remove-Item](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/remove-item)|
|rm|[erase](https://docs.microsoft.com/windows-server/administration/windows-commands/erase)|[Remove-Item](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/remove-item)|
|tail||[Get-Content -Tail 10](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Management/Get-Content)|
|touch||[New-Item -ItemType File](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/new-item)|
|unzip||[Expand-Archive](https://docs.microsoft.com/powershell/module/Microsoft.PowerShell.Archive/Expand-Archive)|
|xdg-open<sup>2</sup>|[start](https://docs.microsoft.com/windows-server/administration/windows-commands/start)|[Start-Process](https://docs.microsoft.com/powershell/module/microsoft.powershell.management/start-process)|

**Notes**

<sup>1</sup> macOS

<sup>2</sup> Linux

## References

- [PowerShell](https://docs.microsoft.com/powershell/scripting/overview). Then click on Reference at the end of the TOC on the left side.
- [Windows Commands](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)
