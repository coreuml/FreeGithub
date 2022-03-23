# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.237.76.137
camo.githubusercontent.com 44.192.1.157
github.map.fastly.net 44.192.89.254
github.global.ssl.fastly.net 3.84.87.226
github.com 54.146.250.7
api.github.com 52.87.182.167
raw.githubusercontent.com 44.192.1.157
favicons.githubusercontent.com 104.209.158.39
avatars5.githubusercontent.com 3.239.93.96
avatars4.githubusercontent.com 3.85.167.153
avatars3.githubusercontent.com 54.159.69.200
avatars2.githubusercontent.com 54.198.72.134
avatars1.githubusercontent.com 44.201.242.160
avatars0.githubusercontent.com 35.170.192.243
# Github Host End
```

更新时间：2022-03-23 13:34:07

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder