# README

A lightweight poc/exp search tool

## Usage

-h: 

get help information

```
>>>./pocSearch -h
Usage of ./pocSearch-linux-amd64:
  -CVE string
        -CVE=CVE-2017-7494
```

-CVE:

search by CVE ID

```
>>>./pocSearch -CVE=CVE-2017-7494
output:
sougou: https://weixin.sogou.com/weixin?type=2&query=CVE-2017-7494&s_from=input&ie=utf8&_sug_=n&_sug_type_=
metasploit: https://github.com/rapid7/metasploit-framework/blob/master/documentation/modules/exploit/linux/samba/is_known_pipename.md
github: https://github.com/opsxcq/exploit-CVE-2017-7494
exploitDB: https://github.com/offensive-security/exploitdb/blob/master/exploits/linux/remote/42060.py
vulhub: https://github.com/vulhub/vulhub/blob/master/samba/CVE-2017-7494/README.md
seebug: None

```

