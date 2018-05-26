---
Name: Netsh.exe
Description: Execute, Surveillance
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "netsh trace start capture=yes filemode=append persistent=yes tracefile=\\\
      \\server\\share\\file.etl    \nnetsh trace show status    \n    \nnetsh.exe\
      \ add helper C:\\Path\\file.dll\t\n     \nnetsh interface portproxy add v4tov4\
      \ listenport=8080 listenaddress=0.0.0.0 connectport=8000 connectaddress=192.168.1.1"
    Description: ''
Full Path:
  - c:\windows\system32\netsh.exe
  - c:\windows\sysWOW64\netsh.exe
Code Sample: []
Detection: []
Resources:
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Persistence/Netsh_Helper_DLL.md
  - https://attack.mitre.org/wiki/Technique/T1128
  - https://twitter.com/teemuluotio/status/990532938952527873
Notes: 'Thanks to '
---