---
Name: Diskshadow.exe
Description: Execute, Dump NTDS.dit
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: diskshadow.exe /s c:\test\diskshadow.txt
    Description: Execute commands using diskshadow.exe from a prepared diskshadow script.
  - Command: diskshadow> exec calc.exe
    Description: Execute a calc.exe using diskshadow.exe.
Full Path:
  - c:\windows\system32\diskshadow.exe
  - c:\windows\sysWOW64\diskshadow.exe
Code Sample: []
Detection: []
Resources:
  - https://bohops.com/2018/03/26/diskshadow-the-return-of-vss-evasion-persistence-and-active-directory-database-extraction/
Notes: Thanks to Jimmy - @bohops

