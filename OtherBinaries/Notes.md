---
Name: Notes.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: Notes.exe" "=N:\Lotus\Notes\Data\notes.ini" -Command if((Get-ExecutionPolicy
      ) -ne AllSigned) { Set-ExecutionPolicy -Scope Process Bypass }
    Description: ''
Full Path:
  - 'C:\Program Files (x86)\IBM\Lotus\Notes\notes.exe    '
Code Sample: []
Detection: []
Resources:
  - https://gist.github.com/danielbohannon/50ec800e92a888b7d45486e5733c359f
  - https://twitter.com/HanseSecure/status/995578436059127808
Notes: 'Thanks to Daniel Bohannon - @danielhbohannon   '
---