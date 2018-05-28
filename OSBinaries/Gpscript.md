---
Name: Gpscript.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: Gpscript /logon
    Description: 'Executes logon scripts configured in Group Policy.'
  - Command: Gpscript /startup
    Description: 'Executes startup scripts configured in Group Policy.'
Full Path:
  - c:\windows\system32\gpscript.exe
  - c:\windows\sysWOW64\gpscript.exe
Code Sample: []
Detection: []
Resources:
  - https://oddvar.moe/2018/04/27/gpscript-exe-another-lolbin-to-the-list/
Notes: |
    Thanks to Oddvar Moe - @oddvarmoe
    Requires administrative rights and modifications to local group policy settings.
---
