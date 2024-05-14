Shadowsocks-Rust

搭建 Shadowsocks-Rust 代理脚本，支持 Debian、Ubuntu、Centos，并支持甲骨文ARM平台。


安装 SS-Rust：

```
wget https://raw.githubusercontent.com/yang12me/ss-rust/main/ss-rust.sh && bash ss-rust.sh
```

更多的协议安装脚本，参考原作者的仓库：
https://github.com/yeahwu/v2ray-wss


搭建 Shadowsocks-rust， V2ray+ Nginx + WebSocket 和 Reality, Hysteria2 代理脚本，支持 Debian、Ubuntu、Centos，并支持甲骨文ARM平台。

简单点讲，没域名的用户可以安装 Reality 和 hy2 代理，有域名的可以安装 V2ray+ Nginx + WebSocket 代理，各取所需。


**便宜VPS推荐：** https://hostalk.net/deals.html

![image](https://github.com/yeahwu/v2ray-wss/assets/13328328/99ce2c9b-4e00-490c-8469-acb65174c912)

已测试系统如下：

Debian 9, 10, 11, 12

Ubuntu 16.04, 18.04, 20.04, 22.04

CentOS 7

编辑配置文件：`nano /etc/shadowsocks/config.json`

查看配置文件：`cat /etc/shadowsocks/config.json`

重启服务：`systemctl restart shadowsocks`

Shadowsocks客户端配置信息：
`cat /etc/shadowsocks/config.json`


卸载方法如下：
https://1024.day/d/1296

**提醒：连不上的朋友，建议先检查一下服务器自带防火墙有没有关闭？**
