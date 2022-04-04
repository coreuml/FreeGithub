# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.159.229.158
camo.githubusercontent.com 3.93.80.140
github.map.fastly.net 3.82.122.163
github.global.ssl.fastly.net 44.198.182.100
github.com 54.236.40.249
api.github.com 3.236.245.168
raw.githubusercontent.com 3.91.193.137
favicons.githubusercontent.com 3.87.141.191
avatars5.githubusercontent.com 107.23.223.198
avatars4.githubusercontent.com 34.232.62.152
avatars3.githubusercontent.com 44.198.182.100
avatars2.githubusercontent.com 3.84.129.125
avatars1.githubusercontent.com 3.233.219.3
avatars0.githubusercontent.com 54.242.32.203
# Github Host End
```

更新时间：2022-04-04 13:35:08

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder