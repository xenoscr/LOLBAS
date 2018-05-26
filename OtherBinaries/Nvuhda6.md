---
Name: Nvuhda6.exe
Description: Execute, Copy, Add registry, Create shortcut, kill process
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "nvuhda6.exe System calc.exe    \n    \nnvuhda6.exe Copy test.txt,test-2.txt\
      \     \n    \nnvuhda6.exe SetReg HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\\
      CurrentVersion\\Run\\malware=malware.exe     \n    \nnvuhda6.exe CreateShortcut\
      \ test.lnk,\"Test\",\"c:\\windows\\system32\\calc.exe\",\"\",\"c:\\windows\\\
      system32\"     \n    \nnvuhda6.exe KillApp calculator.exe     \n   \nnvuhda6.exe\
      \ Run foo"
    Description: ''
Full Path:
  - '?'
Code Sample: []
Detection: []
Resources:
  - http://www.hexacorn.com/blog/2017/11/10/reusigned-binaries-living-off-the-signed-land/
Notes: Thanks to Adam - @hexacorn
---