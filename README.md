# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 52.90.201.147
camo.githubusercontent.com 54.85.37.100
github.map.fastly.net 3.85.238.178
github.global.ssl.fastly.net 34.238.41.84
github.com 54.210.96.225
api.github.com 44.202.158.34
raw.githubusercontent.com 18.212.91.49
favicons.githubusercontent.com 52.90.201.147
avatars5.githubusercontent.com 34.238.41.84
avatars4.githubusercontent.com 18.207.134.2
avatars3.githubusercontent.com 18.206.99.69
avatars2.githubusercontent.com 3.231.224.225
avatars1.githubusercontent.com 3.236.75.73
avatars0.githubusercontent.com 3.236.75.73
# Github Host End
```

更新时间：2022-05-09 13:39:42

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder