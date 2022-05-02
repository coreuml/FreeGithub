# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 18.206.180.84
camo.githubusercontent.com 3.84.120.158
github.map.fastly.net 3.235.233.80
github.global.ssl.fastly.net 54.175.35.118
github.com 107.20.96.254
api.github.com 3.238.205.109
raw.githubusercontent.com 34.203.212.197
favicons.githubusercontent.com 107.20.96.254
avatars5.githubusercontent.com 3.80.181.101
avatars4.githubusercontent.com 3.238.205.109
avatars3.githubusercontent.com 54.80.99.11
avatars2.githubusercontent.com 54.81.103.45
avatars1.githubusercontent.com 3.84.120.158
avatars0.githubusercontent.com 18.206.136.174
# Github Host End
```

更新时间：2022-05-02 13:46:46

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder