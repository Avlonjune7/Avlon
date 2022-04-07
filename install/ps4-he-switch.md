# PS4和Switch



![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233511.jpg)

很多小伙伴的PS4不知道怎么代理上网，以至于下载游戏或者什么东西非常慢，于是这篇教程就出来了。

PS4或者switch使用clash来代理需要满足2个条件：

* 一台Windows系统的电脑
* 当然，你还是得有一台PS4。

配置直接确保你clash客户端在电脑端能正常使用，PS4是使用电脑共享的网络使用clash软件的，PS4使用期间电脑必须开机联网打开clash。并且电脑和PS4必须在一个局域网内（可以理解成使用同一个路由器或者连接同一个Wifi）。

先看这个教程配置好电脑环境

{% content-ref url="win.md" %}
[win.md](win.md)
{% endcontent-ref %}

### Clash配置

首先在电脑的clash客户端里面启用“允许来自局域网的连接”，如下图：

![image-20210825232341020](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825232341.png)

这个时候已经显示出了你局域网IP地址了 那个以太网就是

第二种方法：

也可以手动查看一下电脑的局域网IP地址。具体做法是用Win键+R 快捷键调出“运行”窗口，在此窗口中输入CMD然后确定，调出命令窗口。在命令窗口中输入ipconfig然后回车。 ipconfig会显示出电脑的IP地址等信息。类似下图，从中可以看到电脑的IP地址。

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825232459.png)

后记住自己电脑的IP之我们就去PS4配置了。

### PS4设置教程

打开设定：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825232756.jpg)

选择网络：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825232810.jpg)

设置网络连接：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825232943.jpg)

选择使用WIFI（当然你选择LAN也可以，都是一样设置，我这里是连WIFI就演示WIFI的设置方法）

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825232950.jpg)

然后选择自定：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825232955.jpg)

选择你家的WIFI：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233001.jpg)

IP地址设定这里选择自动：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233008.jpg)

DHCP Host Name这里默认不指定：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233015.jpg)

DNS设定也是默认自动：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233024.jpg)

MTU自动：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233030.jpg)

Proxy(代理)服务器这里选择**使用：**

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233034.jpg)

**然后地址填你电脑的IP，前面有说，Port(端口)码填7890，一般默认是7890**，（如果是 v2ray，这里应该是10808）如图：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233224.jpg)

一般这个端口怎么填你可以直接看clash首页

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233250.png)

然后点继续，会提示已更新网络设置：

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233044.jpg)

然后测试一下就好了，全部OK就设置完毕了\~

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/20210825233047.jpg)

这个时候PS4已经完成代理上网了。
