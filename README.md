# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 44.200.171.70
camo.githubusercontent.com 54.90.217.29
github.map.fastly.net 3.92.183.147
github.global.ssl.fastly.net 3.84.10.69
github.com 3.86.211.183
api.github.com 54.209.216.3
raw.githubusercontent.com 3.237.86.190
favicons.githubusercontent.com 107.23.137.150
avatars5.githubusercontent.com 3.84.10.69
avatars4.githubusercontent.com 3.238.68.17
avatars3.githubusercontent.com 3.92.234.174
avatars2.githubusercontent.com 44.200.103.168
avatars1.githubusercontent.com 44.200.103.168
avatars0.githubusercontent.com 3.230.142.126
# Github Host End
```

更新时间：2022-03-09 13:34:16

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder