# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 44.203.188.212
camo.githubusercontent.com 3.236.20.37
github.map.fastly.net 54.175.211.142
github.global.ssl.fastly.net 184.73.138.97
github.com 3.235.241.153
api.github.com 54.175.211.142
raw.githubusercontent.com 44.193.2.63
favicons.githubusercontent.com 3.83.237.59
avatars5.githubusercontent.com 54.175.211.142
avatars4.githubusercontent.com 54.88.147.144
avatars3.githubusercontent.com 3.234.144.83
avatars2.githubusercontent.com 184.73.138.97
avatars1.githubusercontent.com 3.238.228.102
avatars0.githubusercontent.com 54.234.125.120
# Github Host End
```

更新时间：2022-04-27 13:44:43

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder