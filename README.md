# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.167.252.132
camo.githubusercontent.com 44.202.247.111
github.map.fastly.net 34.231.122.84
github.global.ssl.fastly.net 3.236.64.255
github.com 3.238.12.133
api.github.com 54.86.251.173
raw.githubusercontent.com 3.238.95.53
favicons.githubusercontent.com 54.83.104.253
avatars5.githubusercontent.com 54.90.128.71
avatars4.githubusercontent.com 100.26.102.42
avatars3.githubusercontent.com 54.160.33.103
avatars2.githubusercontent.com 100.26.102.42
avatars1.githubusercontent.com 3.83.29.103
avatars0.githubusercontent.com 3.238.12.133
# Github Host End
```

更新时间：2022-02-23 13:33:32

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder