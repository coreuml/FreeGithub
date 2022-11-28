# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.164.128.135
camo.githubusercontent.com 52.202.65.78
github.map.fastly.net 151.101.1.6
github.global.ssl.fastly.net 151.101.1.6
github.com 140.82.112.3
api.github.com 140.82.112.3
raw.githubusercontent.com 54.221.4.235
favicons.githubusercontent.com 54.91.94.124
avatars5.githubusercontent.com 3.230.162.52
avatars4.githubusercontent.com 44.199.231.82
avatars3.githubusercontent.com 107.23.249.108
avatars2.githubusercontent.com 3.235.176.44
avatars1.githubusercontent.com 3.230.162.52
avatars0.githubusercontent.com 3.222.207.237
# Github Host End
```

更新时间：2022-11-28 13:34:53

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder