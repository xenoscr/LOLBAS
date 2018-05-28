---
Name: Forfiles.exe
Description: Execute, Read ADS
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: forfiles /p c:\windows\system32 /m notepad.exe /c calc.exe
    Description: 'Executes calc.exe since there is a match for notepad.exe in the c:\\windows\\System32 folder.'
  - Command: forfiles /p c:\windows\system32 /m notepad.exe /c "c:\folder\normal.dll:evil.exe"
    Description: 'Executes the evil.exe Alternate Data Stream (AD) since there is a match for notepad.exe in the c:\\windows\\system32 folder.'
Full Path:
  - C:\Windows\system32\forfiles.exe
  - C:\Windows\sysWOW64\forfiles.exe
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/vector_sec/status/896049052642533376
  - https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f
  - https://oddvar.moe/2018/01/14/putting-data-in-alternate-data-streams-and-how-to-execute-it/
Notes: Thanks to Eric - @vector_sec, Oddvar Moe - @oddvarmoe
---
