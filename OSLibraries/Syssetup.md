---
Name: Syssetup.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32 syssetup,SetupInfObjectInstallAction DefaultInstall 128 c:\temp\calc.INF
    Description: Launch an executable file via the SetupInfObjectInstallAction function and .inf file section directive.
  - Command: rundll32.exe syssetup.dll,SetupInfObjectInstallAction DefaultInstall 128 c:\\test\\shady.inf
    Description: Remote fetch and execute a COM Scriptlet by calling an information file directive.
Full Path:
  - c:\windows\system32\Syssetup.dll
  - c:\windows\sysWOW64\Syssetup.dll
Code Sample:
  - https://raw.githubusercontent.com/huntresslabs/evading-autoruns/master/shady.inf
  - https://gist.github.com/enigma0x3/469d82d1b7ecaf84f4fb9e6c392d25ba#file-backdoor-minimalist-sct
  - https://gist.githubusercontent.com/bohops/0cc6586f205f3691e04a1ebf1806aabd/raw/baf7b29891bb91e76198e30889fbf7d6642e8974/calc_exe.inf
Detection: []
Resources:
  - https://twitter.com/pabraeken/status/994392481927258113
  - https://twitter.com/harr0ey/status/975350238184697857
  - https://twitter.com/bohops/status/975549525938135040
Notes: Thanks to Pierre-Alexandre Braeken - @pabraeken (Execute), Matt harr0ey - @harr0ey (Execute), Jimmy - @bohops (COM Scriptlet)
---