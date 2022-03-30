# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 44.203.26.190
camo.githubusercontent.com 54.210.176.61
github.map.fastly.net 54.86.205.229
github.global.ssl.fastly.net 3.238.121.71
github.com 34.200.229.20
api.github.com 34.200.229.20
raw.githubusercontent.com 44.192.117.184
favicons.githubusercontent.com 34.200.229.20
avatars5.githubusercontent.com 3.84.165.215
avatars4.githubusercontent.com 3.85.231.7
avatars3.githubusercontent.com 3.82.174.71
avatars2.githubusercontent.com 34.238.250.238
avatars1.githubusercontent.com 54.197.217.131
avatars0.githubusercontent.com 44.201.25.53
# Github Host End
```

更新时间：2022-03-30 13:34:55

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder