---
Name: CL_Invocation.ps1
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: . C:\\Windows\\diagnostics\\system\\AERO\\CL_Invocation.ps1   \nSyncInvoke <executable> [args]
    Description: Import the PowerShell Diagnostic CL_Invocation script and call SyncInvoke to launch an executable.
Full Path:
  - C:\Windows\diagnostics\system\AERO\CL_Invocation.ps1
  - C:\Windows\diagnostics\system\Audio\CL_Invocation.ps1
  - C:\Windows\diagnostics\system\WindowsUpdate\CL_Invocation.ps1
Code Sample: []
Detection: []
Resources:
  - https://bohops.com/2018/01/07/executing-commands-and-bypassing-applocker-with-powershell-diagnostic-scripts/
  - https://twitter.com/bohops/status/948548812561436672
  - https://twitter.com/pabraeken/status/995107879345704961
Notes: Thanks to Jimmy - @bohops (Execute), Pierre-Alexandre Braeken - @pabraeken (Audio + WindowsUpdate Paths)
---