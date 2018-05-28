---
Name: Url.dll
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe url.dll,OpenURL "C:\\test\\calc.hta"
    Description: Launch a HTML application payload by calling OpenURL.
  - Command: rundll32.exe url.dll,OpenURL "C:\\test\\calc.url"
    Description: Launch an executable payload via proxy through a(n) URL (information) file by calling OpenURL.
  - Command: rundll32.exe url.dll,OpenURL file://^C^:^/^W^i^n^d^o^w^s^/^s^y^s^t^e^m^3^2^/^c^a^l^c^.^e^x^e
    Description: Launch an executable payload by calling OpenURL.
  - Command: rundll32.exe url.dll,FileProtocolHandler calc.exe
    Description: Launch an executable payload by calling FileProtocolHandler.
  - Command: rundll32.exe url.dll,FileProtocolHandler file:///C:/test/test.hta
    Description: Launch a HTML application payload by calling FileProtocolHandler.
  - Command: rundll32 url.dll,FileProtocolHandler file://^C^:^/^W^i^n^d^o^w^s^/^s^y^s^t^e^m^3^2^/^c^a^l^c^.^e^x^e
    Description: Launch an executable payload by calling FileProtocolHandler.

Full Path:
  - c:\windows\system32\url.dll
  - c:\windows\sysWOW64\url.dll
Code Sample:
  - https://gist.githubusercontent.com/bohops/89d7b11fa32062cfe31be9fdb18f050e/raw/1206a613a6621da21e7fd164b80a7ff01c5b64ab/calc.url
Detection: []
Resources:
  - https://bohops.com/2018/03/17/abusing-exported-functions-and-exposed-dcom-interfaces-for-pass-thru-command-execution-and-lateral-movement/
  - https://twitter.com/bohops/status/974043815655956481
  - https://twitter.com/DissectMalware/status/995348436353470465
  - https://twitter.com/yeyint_mth/status/997355558070927360
  - https://twitter.com/Hexacorn/status/974063407321223168
Notes: Thanks to Jimmy - @bohops (OpenURL), Adam - @hexacorn (OpenURL), Malwrologist - @DissectMalware (FileProtocolHandler - HTA), r0lan - @yeyint_mth (Obfuscation)
---