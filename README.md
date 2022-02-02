# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.235.55.237
camo.githubusercontent.com 34.235.152.106
github.map.fastly.net 44.197.213.245
github.global.ssl.fastly.net 34.238.121.40
github.com 54.236.192.214
api.github.com 20.110.132.155
raw.githubusercontent.com 3.80.48.211
favicons.githubusercontent.com 18.232.178.167
avatars5.githubusercontent.com 34.238.121.40
avatars4.githubusercontent.com 54.235.55.237
avatars3.githubusercontent.com 107.20.71.211
avatars2.githubusercontent.com 54.92.168.60
avatars1.githubusercontent.com 3.80.48.211
avatars0.githubusercontent.com 18.207.157.173
# Github Host End
```

更新时间：2022-02-02 13:33:13

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder