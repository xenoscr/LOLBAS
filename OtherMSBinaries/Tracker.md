---
Name: Tracker.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe
    Description: Use tracker.exe to proxy execution of an arbitrary DLL into another process. Since tracker.exe is also signed it can be used to bypass application whitelisting solutions.
Full Path: ''
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/subTee/status/793151392185589760
  - https://attack.mitre.org/wiki/Execution
  
Notes: Thanks to Casey Smith - @subTee
---