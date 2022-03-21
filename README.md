# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 35.153.144.114
camo.githubusercontent.com 3.223.4.66
github.map.fastly.net 3.239.67.133
github.global.ssl.fastly.net 18.208.186.121
github.com 18.207.143.60
api.github.com 35.175.246.210
raw.githubusercontent.com 3.89.48.162
favicons.githubusercontent.com 3.93.35.4
avatars5.githubusercontent.com 44.201.69.231
avatars4.githubusercontent.com 54.196.112.82
avatars3.githubusercontent.com 3.95.200.161
avatars2.githubusercontent.com 52.55.238.251
avatars1.githubusercontent.com 18.205.19.34
avatars0.githubusercontent.com 100.26.51.108
# Github Host End
```

更新时间：2022-03-21 13:34:06

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder