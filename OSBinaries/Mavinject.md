---
Name: Mavinject.exe
Description: Execute, Read ADS
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "MavInject.exe <PID> /INJECTRUNNING <PATH DLL>\n\nMavInject.exe 3110\
      \ /INJECTRUNNING c:\\folder\\evil.dll     \n   \nmavinject.exe 4172 /INJECTRUNNING\
      \ \"c:\\ads\\file.txt:file.dll\""
    Description: ''
Full Path:
  - C:\Windows\System32\mavinject.exe
  - C:\Windows\SysWOW64\mavinject.exe
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/gN3mes1s/status/941315826107510784
  - https://twitter.com/Hexcorn/status/776122138063409152
  - https://oddvar.moe/2018/01/14/putting-data-in-alternate-data-streams-and-how-to-execute-it/
Notes: Thanks to Giuseppe N3mes1s - @gN3mes1s, Adam - @hexacorn, Oddvar Moe - @oddvarmoe
---