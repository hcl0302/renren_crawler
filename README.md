renren_crawler
=======

# Precondition

**First login in your renren.com and get the cookie！！**

# Test Environment
* OSX Yosemite 10.10.4
* Windows 10
* Python 2.7.9

# Dependencies
* lxml
* requests

Install:
``` shell
$ pip install lxml requests
```
# Config file
`config.ini`

* [cookie]  
your renren.com cookie

* [dir]
the directory where to put your albums

Example：
```
start_dir = '/home/work/me/' or 'E:\renren\'
```
* [person]  
{renren ID} = {Renren Name}
You can look for your renren ID or someone's id in the renren profile url.

Example：
```
123456 = 姓名
```

# Instructions

``` shell
$ python renren_crawler.py
```

