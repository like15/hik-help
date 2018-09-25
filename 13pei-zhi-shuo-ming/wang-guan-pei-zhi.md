# 网关配置 {#基础功能}

---

**步骤 1**登录平台， 下载网关安装文件并安装。![](https://pbsq.hik-cloud.com/static/help/assets/wang-guan-xia-zai.jpg)**步骤 2**进入“社区管理”列表， 获取需要配置的社区网关编号。![](https://pbsq.hik-cloud.com/static/help/assets/wang-guan-bian-hao.jpg)**步骤3**进入网关（Watchdog）安装目录，并打开网关配置文件（HIKCLOUD\EDAG\EDAG\edag.json），配置gatewayCode、EstateEntityCode、HttpServerIp、HttpServerPort， 配置完成后请重新启动网关。如下图：

{

```
"WSSURL":"wss://sq.hik-cloud.com:8085/websocket?gatewayCode=41e8345bc938492fb424fc250bafeab8", 

"EstateEntityCode":"41e8345bc938492fb424fc250bafeab8",

"HttpServerIp":"10.10.83.17",

"HttpServerPort":8808

```

}

参数说明：

gatewayCode： 网关编号

EstateEntityCode：网关编号

HttpServerIp：本机IP

httpServerPort：网关与出入口管理终端对接端口，默认8808。

