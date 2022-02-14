# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 18.205.66.111
camo.githubusercontent.com 54.87.54.133
github.map.fastly.net 54.159.214.2
github.global.ssl.fastly.net 3.88.249.119
github.com 54.226.220.254
api.github.com 54.234.146.111
raw.githubusercontent.com 52.91.131.57
favicons.githubusercontent.com 18.205.66.111
avatars5.githubusercontent.com 54.158.126.155
avatars4.githubusercontent.com 50.19.175.18
avatars3.githubusercontent.com 44.195.83.227
avatars2.githubusercontent.com 18.208.209.72
avatars1.githubusercontent.com 52.54.57.208
avatars0.githubusercontent.com 52.91.131.57
# Github Host End
```

更新时间：2022-02-14 13:33:26

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder