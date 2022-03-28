# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.239.184.142
camo.githubusercontent.com 52.3.222.95
github.map.fastly.net 54.85.61.78
github.global.ssl.fastly.net 54.91.17.17
github.com 3.239.148.78
api.github.com 18.212.69.43
raw.githubusercontent.com 3.91.235.38
favicons.githubusercontent.com 18.212.220.40
avatars5.githubusercontent.com 52.91.249.2
avatars4.githubusercontent.com 3.94.83.201
avatars3.githubusercontent.com 3.239.148.78
avatars2.githubusercontent.com 20.94.93.0
avatars1.githubusercontent.com 52.91.249.2
avatars0.githubusercontent.com 3.89.161.187
# Github Host End
```

更新时间：2022-03-28 13:34:24

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder