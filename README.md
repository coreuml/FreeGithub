# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.234.177.232
camo.githubusercontent.com 18.206.191.68
github.map.fastly.net 54.91.167.231
github.global.ssl.fastly.net 100.26.31.95
github.com 3.237.47.90
api.github.com 44.197.173.204
raw.githubusercontent.com 54.164.41.177
favicons.githubusercontent.com 3.238.91.231
avatars5.githubusercontent.com 44.200.186.97
avatars4.githubusercontent.com 34.236.38.3
avatars3.githubusercontent.com 54.204.236.147
avatars2.githubusercontent.com 34.239.156.190
avatars1.githubusercontent.com 54.80.215.47
avatars0.githubusercontent.com 54.167.243.116
# Github Host End
```

更新时间：2022-02-07 13:33:27

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder