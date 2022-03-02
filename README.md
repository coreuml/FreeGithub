# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.83.242.88
camo.githubusercontent.com 100.26.107.48
github.map.fastly.net 3.228.6.24
github.global.ssl.fastly.net 54.174.132.118
github.com 34.207.198.22
api.github.com 35.175.200.22
raw.githubusercontent.com 184.73.104.13
favicons.githubusercontent.com 34.203.195.85
avatars5.githubusercontent.com 54.174.115.88
avatars4.githubusercontent.com 44.203.92.75
avatars3.githubusercontent.com 54.225.21.162
avatars2.githubusercontent.com 34.228.77.24
avatars1.githubusercontent.com 54.205.20.19
avatars0.githubusercontent.com 3.235.138.47
# Github Host End
```

更新时间：2022-03-02 13:33:39

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder