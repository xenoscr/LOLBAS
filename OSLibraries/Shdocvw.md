---
Name: Shdocvw.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe shdocvw.dll,OpenURL "C:\test\calc.url"
    Description: Launch an executable payload via proxy through a(n) URL (information) file by calling OpenURL.
  - Command: rundll32.exe shdocvw.dll,OpenURL "C:\test\calc.zz"
    Description: Renamed URL file.
Full Path:
  - c:\windows\system32\Shdocvw.dll
  - c:\windows\sysWOW64\Shdocvw.dll
Code Sample:
  - https://gist.githubusercontent.com/bohops/89d7b11fa32062cfe31be9fdb18f050e/raw/1206a613a6621da21e7fd164b80a7ff01c5b64ab/calc.url
Detection: []
Resources:
  - http://www.hexacorn.com/blog/2018/03/15/running-programs-via-proxy-jumping-on-a-edr-bypass-trampoline-part-5/
  - https://bohops.com/2018/03/17/abusing-exported-functions-and-exposed-dcom-interfaces-for-pass-thru-command-execution-and-lateral-movement/
  - https://twitter.com/bohops/status/997690405092290561
Notes: Thanks to Adam - @hexacorn, Jimmy - @bohops
---