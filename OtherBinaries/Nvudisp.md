---
Name: Nvudisp.exe
Description: Execute, Copy, Add registry, Create shortcut, kill process
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "Nvudisp.exe System calc.exe    \n    \nNvudisp.exe Copy test.txt,test-2.txt\
      \     \n    \nNvudisp.exe SetReg HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\\
      CurrentVersion\\Run\\malware=malware.exe     \n    \nNvudisp.exe CreateShortcut\
      \ test.lnk,\"Test\",\"c:\\windows\\system32\\calc.exe\",\"\",\"c:\\windows\\\
      system32\"     \n    \nNvudisp.exe KillApp calculator.exe     \n   \nNvudisp.exe\
      \ Run foo"
    Description: ''
Full Path:
  - '?'
Code Sample: []
Detection: []
Resources:
  - http://sysadminconcombre.blogspot.ca/2018/04/run-system-commands-through-nvidia.html
Notes: Thanks to Pierre-Alexandre Braeken - @pabraeken
---