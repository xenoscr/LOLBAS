---
Name: Regsvcs.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: regsvcs.exe AllTheThingsx64.dll
    Description: Loads the target .DLL file and executes the RegisterClass function.
Full Path:
  - C:\Windows\Microsoft.NET\Framework\v2.0.50727\regsvcs.exe
  - C:\Windows\Microsoft.NET\Framework64\v2.0.50727\regsvcs.exe
  - C:\Windows\Microsoft.NET\Framework\v4.0.30319\regsvcs.exe
  - C:\Windows\Microsoft.NET\Framework64\v4.0.30319\regsvcs.exe
Code Sample: []
Detection: []
Resources:
  - https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Payloads/RegSvcsRegAsmBypass.cs
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/RegsvcsRegasm.md
  - https://oddvar.moe/2017/12/13/applocker-case-study-how-insecure-is-it-really-part-1/
Notes: Thanks to Casey Smith - @subtee

