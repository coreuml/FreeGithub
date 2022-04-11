# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 52.90.24.98
camo.githubusercontent.com 3.87.101.187
github.map.fastly.net 3.224.135.153
github.global.ssl.fastly.net 3.84.184.5
github.com 13.89.201.207
api.github.com 34.238.191.0
raw.githubusercontent.com 34.228.30.9
favicons.githubusercontent.com 18.204.216.221
avatars5.githubusercontent.com 34.232.48.169
avatars4.githubusercontent.com 18.214.36.3
avatars3.githubusercontent.com 3.80.2.212
avatars2.githubusercontent.com 54.211.220.71
avatars1.githubusercontent.com 3.224.135.153
avatars0.githubusercontent.com 52.90.118.39
# Github Host End
```

更新时间：2022-04-11 13:35:26

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder