---
Name: Advpack.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "rundll32.exe advpack.dll,LaunchINFSection c:\\test.inf,DefaultInstall_SingleUser,1,\
      \     \nrundll32.exe advpack.dll,RegisterOCX calc.exe"
    Description: ''
Full Path:
  - c:\windows\system32\advpack.dll
  - c:\windows\sysWOW64\advpack.dll
Code Sample: []
Detection: []
Resources:
  - https://bohops.com/2018/02/26/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion-persistence/
  - https://twitter.com/ItsReallyNick/status/967859147977850880
  - https://twitter.com/bohops/status/974497123101179904
Notes: Thanks to Jimmy - @bohops
---