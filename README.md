# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.205.157.114
camo.githubusercontent.com 3.235.236.50
github.map.fastly.net 151.101.1.6
github.global.ssl.fastly.net 151.101.1.6
github.com 140.82.114.4
api.github.com 140.82.114.4
raw.githubusercontent.com 44.202.36.89
favicons.githubusercontent.com 54.81.29.82
avatars5.githubusercontent.com 3.82.244.227
avatars4.githubusercontent.com 34.229.48.151
avatars3.githubusercontent.com 3.235.88.199
avatars2.githubusercontent.com 3.94.144.15
avatars1.githubusercontent.com 54.89.100.17
avatars0.githubusercontent.com 3.235.31.236
# Github Host End
```

更新时间：2022-08-03 13:52:46

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder