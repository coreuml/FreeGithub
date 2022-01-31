# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 44.202.72.160
camo.githubusercontent.com 34.230.84.197
github.map.fastly.net 44.197.242.73
github.global.ssl.fastly.net 44.192.130.246
github.com 18.205.66.67
api.github.com 34.231.180.75
raw.githubusercontent.com 54.145.9.60
favicons.githubusercontent.com 3.85.241.203
avatars5.githubusercontent.com 54.152.14.141
avatars4.githubusercontent.com 3.239.169.44
avatars3.githubusercontent.com 3.87.59.8
avatars2.githubusercontent.com 54.234.163.120
avatars1.githubusercontent.com 44.197.242.73
avatars0.githubusercontent.com 34.239.179.245
# Github Host End
```

更新时间：2022-01-31 13:33:24

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder