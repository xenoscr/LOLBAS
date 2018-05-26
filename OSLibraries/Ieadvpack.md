---
Name: Ieadvpack.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe ieadvpack.dll,LaunchINFSection test.inf,,1,
    Description: ''
  - Command: rundll32.exe IEAdvpack.dll,RegisterOCX calc.exe
    Description: ''
Full Path:
  - c:\windows\system32\ieadvpack.dll
  - c:\windows\sysWOW64\ieadvpack.dll
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/pabraeken/status/991695411902599168
  - https://bohops.com/2018/03/10/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion-persistence-part-2/
Notes: Thanks to Pierre-Alexandre Braeken - @pabraeken (RegisterOCX), Jimmy - @bohops
---