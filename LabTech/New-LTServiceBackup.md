# New-LTServiceBackup
## SYNOPSIS
This function will backup all the reg keys to 'HKLM\SOFTWARE\LabTechBackup'
This will also backup those files to "$((Get-LTServiceInfo).BasePath)Backup"
## SYNTAX
```powershell
New-LTServiceBackup [<CommonParameters>]
```
## NOTES
Version:        1.4

Author:         Chris Taylor

Website:        labtechconsulting.com

Creation Date:  5/11/2017

Purpose/Change: Initial script development



Update Date: 6/1/2017

Purpose/Change: Updates for better overall compatibility, including better support for PowerShell V2



Update Date: 6/7/2017

Purpose/Change: Updated error handling.



Update Date: 8/24/2017

Purpose/Change: Update to use Clear-Variable.



Update Date: 3/21/2017

Purpose/Change: Added additional Debug Output 
