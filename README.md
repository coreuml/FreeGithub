# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.236.84.103
camo.githubusercontent.com 3.238.5.121
github.map.fastly.net 44.199.244.228
github.global.ssl.fastly.net 44.199.244.228
github.com 54.144.23.31
api.github.com 184.73.24.167
raw.githubusercontent.com 54.198.120.12
favicons.githubusercontent.com 184.73.24.167
avatars5.githubusercontent.com 52.176.43.70
avatars4.githubusercontent.com 54.89.164.225
avatars3.githubusercontent.com 3.235.107.203
avatars2.githubusercontent.com 3.237.255.96
avatars1.githubusercontent.com 54.210.120.181
avatars0.githubusercontent.com 54.144.23.31
# Github Host End
```

更新时间：2022-03-14 13:48:34

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder