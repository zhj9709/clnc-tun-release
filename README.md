## clnc-tun

### v2.0

1. 默认禁止ipv6联网
2. 清除规则用了while循环，防止有多个重复的规则一次清不掉

### v2.1

1. 修复一些内网未放行的问题
2. 可以用tls了(`method="GET:tls"`)
3. 更新了busybox(v1.31.1)

