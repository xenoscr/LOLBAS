---
Name: Ieframe.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe ieframe.dll,OpenURL "C:\test\calc.url"
    Description: ''
Full Path:
  - c:\windows\system32\Ieframe.dll
  - c:\windows\sysWOW64\Ieframe.dll
Code Sample: []
Detection: []
Resources:
  - http://www.hexacorn.com/blog/2018/03/15/running-programs-via-proxy-jumping-on-a-edr-bypass-trampoline-part-5/
  - https://bohops.com/2018/03/17/abusing-exported-functions-and-exposed-dcom-interfaces-for-pass-thru-command-execution-and-lateral-movement/
Notes: Thanks to Adam - @hexacorn, Jimmy - @bohops
---