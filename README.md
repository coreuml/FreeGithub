# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.201.23.246
camo.githubusercontent.com 34.203.215.137
github.map.fastly.net 18.232.250.131
github.global.ssl.fastly.net 3.94.92.234
github.com 3.236.24.22
api.github.com 184.73.53.211
raw.githubusercontent.com 54.210.194.0
favicons.githubusercontent.com 3.90.199.15
avatars5.githubusercontent.com 3.236.17.188
avatars4.githubusercontent.com 3.85.31.212
avatars3.githubusercontent.com 34.203.215.137
avatars2.githubusercontent.com 34.238.172.67
avatars1.githubusercontent.com 3.227.233.160
avatars0.githubusercontent.com 50.16.84.154
# Github Host End
```

更新时间：2022-02-21 13:33:26

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder