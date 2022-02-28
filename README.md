# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.144.49.168
camo.githubusercontent.com 40.121.234.173
github.map.fastly.net 44.197.226.152
github.global.ssl.fastly.net 18.234.223.170
github.com 44.203.78.230
api.github.com 3.80.2.10
raw.githubusercontent.com 52.91.70.239
favicons.githubusercontent.com 44.203.0.63
avatars5.githubusercontent.com 54.144.49.168
avatars4.githubusercontent.com 3.88.35.137
avatars3.githubusercontent.com 34.229.239.68
avatars2.githubusercontent.com 44.203.78.230
avatars1.githubusercontent.com 3.233.229.172
avatars0.githubusercontent.com 54.197.79.203
# Github Host End
```

更新时间：2022-02-28 13:33:35

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder