---
Name: Control.exe
Description: Execute, Read ADS
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: control.exe c:\windows\tasks\file.txt:evil.dll
    Description: Execute evil.dll which is stored in an Alternate Data Stream (ADS).
Full Path:
  - 'C:\Windows\system32\control.exe    '
  - 'C:\Windows\sysWOW64\control.exe     '
Code Sample: []
Detection: []
Resources:
  - https://pentestlab.blog/2017/05/24/applocker-bypass-control-panel/
  - https://www.contextis.com/resources/blog/applocker-bypass-registry-key-manipulation/
  - https://bohops.com/2018/01/23/loading-alternate-data-stream-ads-dll-cpl-binaries-to-bypass-applocker/
  - https://twitter.com/bohops/status/955659561008017409
Notes: Thanks to Jimmy - @bohops

