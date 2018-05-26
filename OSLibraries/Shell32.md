---
Name: Shell32.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe shell32.dll,Control_RunDLL payload.dll
    Description: ''
  - Command: rundll32.exe shell32.dll,ShellExec_RunDLL beacon.exe
    Description: ''
Full Path:
  - c:\windows\system32\shell32.dll
  - c:\windows\sysWOW64\shell32.dll
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/pabraeken/status/991768766898941953
Notes: Thanks to Pierre-Alexandre Braeken - @pabraeken (ShellExec_RunDLL)
---