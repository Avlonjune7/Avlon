# Openwrt/梅林软路由

很多朋友问我电视怎么看奈飞ps4怎么加速器，在这些终端上面装软件其实都不是最优解，最优解是把软件运行在路由器上面，这样连接路由器的所有终端设备都可以进行加速效果，电脑平板电视ps4switch不用额外设置只要连接了路由器wifi就可以达到加速效果，这边我以斐讯k2p刷了openwrt系统为例。

### 准备工作

拼多多可以买到刷好OP系统的k2p（只是以k2p为例子）

其他路由器像斐讯n1 TPLINK路由器也可以刷openwrt固件可以去`恩山无线论坛`看下

华硕的梅林固件可以直接装meirinclash我这边没华硕不演示了

拼多多直接搜k2p路由器 买刷好openwrt系统的

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1616516.jpg)

### openwrt设置视频教程

### 其他固件

## 华硕路由器安装Merlin Clash

## 安装步骤

在安装Merlin Clash之前请先卸载科学上网插件，两者有不兼容现象。以防万一请先卸载。 之后使用软件中心中的虚拟内存，创建一个虚拟内存，以确保路由器有足够运行空间，也将提升效能&#x20;

&#x20;

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622426648664.1cnzhwz7600w.png)

接着我们下载适合我们机型的离线插件安装包即可

### 部分对应机型插件

不知道自己的架构的 输入自己华硕路由器型号百度

* ARM V8 HND 版本 — 20210416 支持 –AC86U –AX86U/AX88U/AX1100 –GT5300等
* ARM V7 AX32版 — 20210416

\*.修改安装脚本判断逻辑 支持 –AX3000/AX82/AX56 –AX56Uv2 –AX89X等

* ARM V7 384/386版本 — 20210416 使用384/386版本固件的ARM V7设备 –AC66U\_B1/AC68U –AC1900/AC1900P –AC87U/AC3200 –AC88U/AC3100 –RT5300等

### 懒人下载地址包含补丁

{% embed url="https://gqzw.lanzouo.com/b05numv6d" %}

在Koolshare软件中心离线上传对应型号的插件安装包即可。

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622426959144.5t8ewdub53w0.png)

![](https://cdn.jsdelivr.net/gh/zxfccmm/image@master/20210722/1622427068021.22iv4pekpatc.png)

![](https://cdn.jsdelivr.net/gh/zxfccmm/image@master/20210722/1622427073720.1tvmbjvipsww.png)

至此Merlin Clash插件安装完毕。 接着，我们进入Merlin Clash插件界面先进行补丁升级。 点击高级模式上传补丁。

![1622](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622427103995.12ooveeb1pmo.png)

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622427113705.z30hvx6dcc0.png)

接着点击配置文件选择合适你的配置文件导入，有关Clash配置文件也可参考之前Shellclash配置文件转换。 Merlin Clash 内置了Clash订阅转换，可添加订阅节点后进行规则的转化。 最后选择你刚刚上传上去的配置文件，并点击开始后，保存。至此Merlin Clash运行开始。

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622427218219.72prs98akq80.png)

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622427225666.40cy283ngmk0.png)

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622427230570.30h3jk672sw0.png)

后端管理地址如下图可自行登录查看节点分组，规则设置等。 管理面板：192.168.50.1:9990 | 面板密码：clash

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622427254027.159cfspw1nz4.png)

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622757102086.7895t6sz2h00.png)

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/1622427266018.68k3vkhzetg0.png)

## 测速分享

最后附带Merlin Clash YouTube 8K视频测速截图。 我用的是电信1000M的网速，仅供参考。当然你的速度和你的运营商以及节点的速度都有关系。

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/image-20211230102922534.png)

### 假如你对安装还有任何疑问请联系售后客服

* [华硕RT-AC86U安装Merlin Clash](https://zxfccmm.cn/hua-shuo-rt-ac86u-an-zhuang-merlin-clash)
* [OpenWrt](https://github.com/vernesong/OpenClash/wiki)
* [Merlin](https://github.com/KOP-XIAO/Clash-Merlin/wiki)
* [Koolshare OpenWrt/LEDE](https://koolclash.js.org)

{.links-list}
