# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.92.63.103
camo.githubusercontent.com 54.80.229.194
github.map.fastly.net 54.163.54.55
github.global.ssl.fastly.net 35.168.58.224
github.com 18.208.187.224
api.github.com 54.91.90.40
raw.githubusercontent.com 3.236.82.254
favicons.githubusercontent.com 35.175.119.130
avatars5.githubusercontent.com 35.172.135.137
avatars4.githubusercontent.com 54.157.26.66
avatars3.githubusercontent.com 34.204.92.172
avatars2.githubusercontent.com 3.218.153.32
avatars1.githubusercontent.com 3.238.173.231
avatars0.githubusercontent.com 54.91.90.40
# Github Host End
```

更新时间：2022-04-13 13:35:35

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder