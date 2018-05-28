---
Name: Advpack.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: |
          rundll32.exe advpack.dll,LaunchINFSection c:\test.inf,DefaultInstall_SingleUser,1,
          rundll32.exe advpack.dll,RegisterOCX calc.exe
    Description: ''
Full Path:
  - C:\Windows\System32\advpack.dll
  - C:\Windows\SysWOW64\advpack.dll
Code Sample: []
Detection: []
Resources:
  - https://bohops.com/2018/02/26/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion-persistence/
  - https://twitter.com/ItsReallyNick/status/967859147977850880
  - https://twitter.com/bohops/status/974497123101179904
Notes: Thanks to Jimmy - @bohops
---