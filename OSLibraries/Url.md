---
Name: Url.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe url.dll,OpenURL "C:\test\calc.hta"
    Description: ''
  - Command: rundll32.exe url.dll,OpenURL "C:\test\calc.url"
    Description: ''
  - Command: rundll32.exe url.dll, FileProtocolHandler calc.exe
    Description: ''
Full Path:
  - c:\windows\system32\url.dll
  - c:\windows\sysWOW64\url.dll
Code Sample: []
Detection: []
Resources:
  - https://bohops.com/2018/03/17/abusing-exported-functions-and-exposed-dcom-interfaces-for-pass-thru-command-execution-and-lateral-movement/
Notes: Thanks to Jimmy - @bohops
---