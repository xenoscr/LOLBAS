---
Name: Setupapi.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32 setupapi,InstallHinfSection DefaultInstall 132 c:\temp\calc.inf
    Description: Launch an executable file via the InstallHinfSection function and .inf file section directive.
  - Command: rundll32.exe setupapi.dll,InstallHinfSection DefaultInstall 128 C:\\Tools\\shady.inf
    Description: Remote fetch and execute a COM Scriptlet by calling an information file directive.
Full Path:
  - c:\windows\system32\Setupapi.dll
  - c:\windows\sysWOW64\Setupapi.dll
Code Sample:
  - https://raw.githubusercontent.com/huntresslabs/evading-autoruns/master/shady.inf
  - https://gist.github.com/enigma0x3/469d82d1b7ecaf84f4fb9e6c392d25ba#file-backdoor-minimalist-sct
  - https://gist.githubusercontent.com/bohops/0cc6586f205f3691e04a1ebf1806aabd/raw/baf7b29891bb91e76198e30889fbf7d6642e8974/calc_exe.inf
Detection: []
Resources:
  - https://twitter.com/pabraeken/status/994742106852941825
  - https://twitter.com/subTee/status/951115319040356352
  - https://twitter.com/KyleHanslovan/status/911997635455852544
  - https://github.com/huntresslabs/evading-autoruns
Notes: Thanks to Pierre-Alexandre Braeken - @pabraeken (Executable), Kyle Hanslovan - @KyleHanslovan (COM Scriptlet), Huntress Labs - @HuntressLabs (COM Scriptlet), Casey Smith - @subTee (COM Scriptlet)
---