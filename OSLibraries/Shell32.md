---
Name: Shell32.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe shell32.dll,Control_RunDLL payload.dll
    Description: Launch DLL payload.
  - Command: rundll32.exe shell32.dll,ShellExec_RunDLL beacon.exe
    Description: Launch executable payload.
  - Command: rundll32 SHELL32.DLL,ShellExec_RunDLL "cmd.exe" "/c echo hi"
    Description: Launch executable payload with arguments.
Full Path:
  - c:\windows\system32\shell32.dll
  - c:\windows\sysWOW64\shell32.dll
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/Hexacorn/status/885258886428725250
  - https://twitter.com/pabraeken/status/991768766898941953
  - https://twitter.com/mattifestation/status/776574940128485376
  - https://twitter.com/KyleHanslovan/status/905189665120149506
Notes: Thanks to Adam - @hexacorn (Control_RunDLL), Pierre-Alexandre Braeken - @pabraeken (ShellExec_RunDLL), Matt Graeber - @mattifestation (ShellExec_RunDLL), Kyle Hanslovan - @KyleHanslovan (ShellExec_RunDLL)
---