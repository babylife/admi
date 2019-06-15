K3 Merlin enable hosts:

1. 开启JFFS 和 SSH 登录
系统管理 > 系统设置 。。。 
然后重启路由器

2. SSH 登录路由器
在/jffs/configs下建一名为dnsmasq.conf.add的文件

在里面写addn-hosts=/jffs/configs/hosts

在/jffs/configs下建自己的 hosts 的文件

执行service restart_dnsmasq重启 dnsmasq 服务（或者重启路由器）

OK, hosts 就生效了。

# ADMI

adblock for xiaomi

import/copy from https://github.com/coderstory/Mi-Purify.
