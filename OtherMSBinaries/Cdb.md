---
Name: Cdb.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: cdb.exe -cf x64_calc.wds -o notepad.exe
    Description: Launch 64-bit shellcode from the x64_calc.wds file using cdb.exe.
Full Path:
  - C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\cdb.exe
  - C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe
Code Sample: []
Detection: []
Resources:
  - http://www.exploit-monday.com/2016/08/windbg-cdb-shellcode-runner.html
  - https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/cdb-command-line-options
  - https://gist.github.com/mattifestation/94e2b0a9e3fe1ac0a433b5c3e6bd0bda
Notes: Thanks to Matt Graeber - @mattifestation
