---
Name: regedit.exe
Description: Write ADS, Read ADS, Import registry
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "regedit /E c:\\ads\\file.txt:regfile.reg HKEY_CURRENT_USER\\MyCustomRegKey\n\
      \    \nregedit c:\\ads\\file.txt:regfile.reg"
    Description: ''
Full Path:
  - c:\windows\system32\regedit.exe
  - c:\windows\sysWOW64\regedit.exe
Code Sample: []
Detection: []
Resources:
  - https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f
Notes: Thanks to Oddvar Moe - @oddvarmoe
---