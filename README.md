# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.211.233.122
camo.githubusercontent.com 54.81.91.149
github.map.fastly.net 54.166.242.160
github.global.ssl.fastly.net 3.84.6.76
github.com 3.214.224.8
api.github.com 44.200.132.66
raw.githubusercontent.com 34.228.189.143
favicons.githubusercontent.com 44.192.75.190
avatars5.githubusercontent.com 54.160.164.32
avatars4.githubusercontent.com 3.238.95.188
avatars3.githubusercontent.com 3.89.157.132
avatars2.githubusercontent.com 3.84.6.76
avatars1.githubusercontent.com 54.163.220.151
avatars0.githubusercontent.com 3.234.239.31
# Github Host End
```

更新时间：2022-04-06 13:35:16

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder