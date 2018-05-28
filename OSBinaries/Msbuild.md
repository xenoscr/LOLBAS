---
Name: Msbuild.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: msbuild.exe pshell.xml
    Description: 'Build and execute a C# project stored in the target XML file.'
  - Command: msbuild.exe Msbuild.csproj
    Description: 'Build and execute a C# project stored in the target CSPROJ file.'
Full Path:
  - C:\Windows\Microsoft.NET\Framework\v2.0.50727\Msbuild.exe
  - C:\Windows\Microsoft.NET\Framework64\v2.0.50727\Msbuild.exe
  - C:\Windows\Microsoft.NET\Framework\v3.5\Msbuild.exe
  - C:\Windows\Microsoft.NET\Framework64\v3.5\Msbuild.exe
  - C:\Windows\Microsoft.NET\Framework\v4.0.30319\Msbuild.exe
  - C:\Windows\Microsoft.NET\Framework64\v4.0.30319\Msbuild.exe
Code Sample: []
Detection: []
Resources:
  - https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/Trusted_Developer_Utilities.md
  - https://github.com/Cn33liz/MSBuildShell
  - https://pentestlab.blog/2017/05/29/applocker-bypass-msbuild/
  - https://oddvar.moe/2017/12/13/applocker-case-study-how-insecure-is-it-really-part-1/
Notes: Thanks to Casey Smith - @subtee, Cn33liz - @Cneelis
---
