# 在 Netch 上配置

## 简介

Netch 是一款 Windows 平台的开源游戏加速工具，Netch 可以实现类似 SocksCap64 那样的进程代理，也可以实现 SSTap 那样的全局 TUN/TAP 代理，和 Shadowsocks-Windows 那样的本地 Socks5，HTTP 和系统代理。至于连接至远程服务器的代理协议，目前 Netch 支持以下代理协议：Shadowsocks，VMess，Socks5，ShadowsocksR

与此同时 Netch 避免了 SSTap 的 NAT 问题 ，检查 NAT 类型即可知道是否有 NAT 问题。使用 SSTap 加速部分 P2P 联机，对 NAT 类型有要求的游戏时，可能会因为 NAT 类型严格遇到无法加入联机，或者其他影响游戏体验的情况

* [官方文档](https://netch.org)
* [项目地址](https://github.com/NetchX)

## 如何使用

### 1.安装依赖

* [Visual C++ 运行库合集](https://www.google.com/search?q=Visual+C%2B%2B+%E8%BF%90%E8%A1%8C%E5%BA%93%E5%90%88%E9%9B%86)
* [.NET Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net48-offline-installer)
* [TAP-Windows](https://build.openvpn.net/downloads/releases/tap-windows-9.21.2.exe)

### 2.下载安装 Netch 并导入订阅

* 1.[官方下载](https://github.com/NetchX/Netch/releases)
* 2.[第三方下载](https://od.nonage.me/home/%E7%A7%91%E5%AD%A6%E4%B8%8A%E7%BD%91%E5%AE%A2%E6%88%B7%E7%AB%AF/Windows/Netch/v1.4.1)

#### 安装完成打开主程序

1.打开程序订阅管理页面

![](https://view.nonage.me/images/2020/07/06/netch01.png)

2.打开官网点开产品页面添加订阅

![](https://view.nonage.me/images/2020/07/06/netch02.png)

3.订阅添加完成！

![](https://view.nonage.me/images/2020/07/06/netch03.png)

4.更新服务器（订阅）

![](https://view.nonage.me/images/2020/07/06/netch04.png)

5.选中服务器连接

![](https://view.nonage.me/images/2020/07/06/netch05.png)

