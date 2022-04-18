# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 20.230.65.187
camo.githubusercontent.com 18.232.49.194
github.map.fastly.net 54.162.247.51
github.global.ssl.fastly.net 54.236.71.23
github.com 18.232.184.45
api.github.com 23.20.2.181
raw.githubusercontent.com 54.236.71.23
favicons.githubusercontent.com 3.226.47.130
avatars5.githubusercontent.com 44.204.60.97
avatars4.githubusercontent.com 3.237.21.117
avatars3.githubusercontent.com 44.199.229.13
avatars2.githubusercontent.com 3.239.53.198
avatars1.githubusercontent.com 44.203.219.239
avatars0.githubusercontent.com 54.91.209.5
# Github Host End
```

更新时间：2022-04-18 13:35:50

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder