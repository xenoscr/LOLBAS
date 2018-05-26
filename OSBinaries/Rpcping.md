---
Name: Rpcping.exe
Description: Credentials
Author: ''
Created: '2018-05-25'
Categories: []
Commands:
  - Command: "rpcping -s 127.0.0.1 -t ncacn_np\n     \nrpcping -s 192.168.1.10 -t\
      \ ncacn_np"
    Description: ''
  - Command: rpcping  -s 127.0.0.1 -e 1234 -a privacy -u NTLM
    Description: ''
Full Path:
  - c:\windows\system32\rpcping.exe
  - c:\windows\sysWOW64\rpcping.exe
Code Sample: []
Detection: []
Resources:
  - https://twitter.com/subtee/status/872797890539913216
  - https://github.com/vysec/RedTips
  - https://twitter.com/vysecurity/status/974806438316072960
  - https://twitter.com/vysecurity/status/873181705024266241
Notes: Thanks to Casey Smith - @subtee, Vincent Yiu - @vysecurity
---