---
Name: Regasm.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: regasm.exe /U AllTheThingsx64.dll
    Description: ''
Full Path:
  - C:\Windows\Microsoft.NET\Framework\v2.0.50727\regasm.exe
  - C:\Windows\Microsoft.NET\Framework64\v2.0.50727\regasm.exe
  - C:\Windows\Microsoft.NET\Framework\v4.0.30319\regasm.exe
  - C:\Windows\Microsoft.NET\Framework64\v4.0.30319\regasm.exe
Code Sample: []
Detection: []
Resources:
  - https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Payloads/RegSvcsRegAsmBypass.cs
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/RegsvcsRegasm.md
  - https://oddvar.moe/2017/12/13/applocker-case-study-how-insecure-is-it-really-part-1/
Notes: Thanks to Casey Smith - @subtee
---