# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.231.241.117
camo.githubusercontent.com 44.204.135.169
github.map.fastly.net 54.161.129.251
github.global.ssl.fastly.net 54.198.160.46
github.com 3.236.149.59
api.github.com 3.227.23.194
raw.githubusercontent.com 3.87.37.171
favicons.githubusercontent.com 3.88.158.84
avatars5.githubusercontent.com 54.161.129.251
avatars4.githubusercontent.com 18.234.191.7
avatars3.githubusercontent.com 44.192.47.243
avatars2.githubusercontent.com 44.202.71.10
avatars1.githubusercontent.com 54.198.160.46
avatars0.githubusercontent.com 34.231.20.57
# Github Host End
```

更新时间：2022-04-25 13:36:31

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder