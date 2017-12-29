---
title: 如何优雅（无限）的使用（试用） versions
date: 2017-10-17 16:48:27
encrypt: true
enc_pwd: damaochina
tags: 
- svn
- 工具集合
---

其实是一篇如何无限试用的教程，仅仅是为了测试和交流，如果有能力的同学请移步[官网](https://www.versionsapp.com)购买正版
 
 本猫的mac升级到了 macos 10.12.6 之后，网上流传的所谓的versions破解版本就不可用了，总会出现闪崩退出的情况。经历了command line + bbeidt 的黑暗时代和 cornerstone 的混乱时代，本猫决定自己尝试破解 versions ， 来一解相思之苦。。。  
 
 第一次胡乱尝试的结果就是我的小mac成功的重装了系统，真心想念我们亲爱的水果出的时间胶囊。。。
 
 废话少说，放出教程。 接招吧，versions君：   
  
 ```
 * 运行chean app软件，清楚残留的versions文件。如果以前的. versions文件已经通过常规方式删除，需去官网下载安装versions，然后利用cleanapp清除；
 * 修改系统时间为versions未过期的时间. 
 * 终端cd到user目录下，依次运行如下命令：
	ps：如需要输入密码为开机密码
	sudo rm ~/.CF89AA64
	sudo rm ~/Library/.FB64CF89
	sudo rm ~/Library/Preferences/com.blackpixel.versions.plist
	sudo open ~/Library/Preferences/.GlobalPreferences.plist        默认为xcode打开
	Delete the key: com.blackpixel.versions.ezsRequiredToken and save it.  
 * 重启机器，然后修改系统时间为自动，即正常时间
 * 安装 versions，试用期为1个月零1天，到期后重复上面操作即可。
 
 ```
 附录 ：[百度云链接](http://pan.baidu.com/s/1kV7Tzjp)   
 PassWord : 9ggv