---
Name: pester.bat
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "# Execute notepad\nPester.bat /help \"$null; notepad\"\n# Execute calc\n\
      Pester.bat /help \"$null; calc\"\n# Execute Get-Process cmdlet\nPester.bat /help\
      \ \"$null; ps\"\n\n# Other options for 2nd parameter\npester.bat help \"$null;\
      \ notepad\"\npester.bat /help \"$null; notepad\"\npester.bat ? \"$null; notepad\"\
      \npester.bat -? \"$null; notepad\"\npester.bat /? \"$null; notepad\"\n\n# 3rd\
      \ parameter can be anything\npester.bat /help \"'doesnotexist'; notepad\"\n\
      pester.bat /help \"Get-Help; notepad\"\npester.bat /help \"gcm;notepad\"\n\n\
      # 4th parameter is the payload"
    Description: ''
Full Path: ''
Code Sample: []
Detection: []
Resources: []
Notes: Thanks to Emin Atac - @p0w3rsh3ll
---