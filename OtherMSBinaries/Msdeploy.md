---
Name: Msdeploy.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: msdeploy.exe -verb:sync -source:RunCommand -dest:runCommand="c:\temp\calc.bat"
    Description: Launch calc.bat via msdeploy.exe.
Full Path:
  - C:\Program Files (x86)\IIS\Microsoft Web Deploy V3\msdeploy.exe
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/pabraeken/status/995837734379032576
Notes: Thanks to Pierre-Alexandre Braeken - @pabraeken
---